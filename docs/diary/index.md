# e fef


  <script src="../../release/go.js"></script>
  <div id="allSampleContent" class="p-4 w-full">
    <script src="../../extensions/HyperlinkText.js"></script>
    <script id="code">
      function init() {

// Since 2.2 you can also author concise templates with method chaining instead of GraphObject.make
// For details, see https://gojs.net/latest/intro/buildingObjects.html
const $ = go.GraphObject.make;

myDiagram =
  $(go.Diagram, "myDiagramDiv",
    { isReadOnly: true, allowSelect: false, contentAlignment: go.Spot.Center });

myDiagram.nodeTemplate =
  $(go.Node, "Auto",
    { locationSpot: go.Spot.Center },
    new go.Binding("location", "loc", go.Point.parse),
    $(go.Shape, "Ellipse",
      { fill: "transparent" },
      new go.Binding("stroke", "color"),
      new go.Binding("strokeWidth", "width"),
      new go.Binding("strokeDashArray", "dash")),
    $("HyperlinkText",
      node => "https://en.wikipedia.org/w/index.php?search=" + encodeURIComponent(node.data.text),
      node => node.data.text,
      { margin: 1, maxSize: new go.Size(80, 80), textAlign: "center" })
  );

myDiagram.nodeTemplateMap.add("center",
  $(go.Node, "Spot",
    { locationSpot: go.Spot.Center },
    new go.Binding("location", "loc", go.Point.parse),
    $(go.Shape, "Circle",
      {
        fill: "rgba(128,128,128,0.1)", stroke: null,
        width: 550, height: 550
      }),
    $(go.Shape, "Circle",
      {
        fill: "rgba(128,128,128,0.05)", stroke: null,
        width: 400, height: 400
      }),
    $(go.Shape, "Circle",
      {
        fill: "rgba(128,128,128,0.033)", stroke: null,
        width: 250, height: 250
      }),
    $(go.Panel, "Spot",
      $(go.Shape, "Circle",
        { isPanelMain: true, fill: "transparent", portId: "" },
        new go.Binding("stroke", "hicolor"),
        new go.Binding("strokeWidth", "hiwidth")),
      $(go.Shape, "Circle",
        { isPanelMain: true, fill: "transparent" },
        new go.Binding("stroke", "color"),
        new go.Binding("strokeWidth", "width"),
        new go.Binding("strokeDashArray", "dash")),
      $("HyperlinkText",
        node => "https://en.wikipedia.org/w/index.php?search=" + encodeURIComponent(node.data.text),
        node => node.data.text,
        { margin: 1, maxSize: new go.Size(80, 80), textAlign: "center" })
    )
  ));

myDiagram.linkTemplate =
  $(go.Link,
    $(go.Shape,
      new go.Binding("stroke", "color"),
      new go.Binding("strokeWidth", "width"),
      new go.Binding("strokeDashArray", "dash"))
  );

var nodeDataArray = [
  { key: 1, text: "Cognitive Procedural", loc: "300 300", category: "center" },
  { key: 2, text: "Cognitive Problem Solving", loc: "600 300", category: "center", hicolor: "lightblue", hiwidth: 7 },
  { key: 11, text: "Logical Reasoning", loc: "450 275" },
  { key: 12, text: "Scaffolding", loc: "450 325" },
  { key: 13, text: "Part Task Training", loc: "425 400" },
  { key: 21, text: "Training Wheels", loc: "325 125" },
  { key: 22, text: "Exploratory Learning", loc: "250 150" },
  { key: 23, text: "Learner Control", loc: "650 150" },
  { key: 31, text: "Overlearning", loc: "450 475" }
];
var linkDataArray = [
  { from: 1, to: 11, color: "gray" },
  { from: 1, to: 12, color: "gray", dash: [3, 2] },
  { from: 1, to: 13, color: "olive", width: 2 },
  { from: 1, to: 21, color: "olive", width: 3 },
  { from: 1, to: 22, color: "olive", width: 2 },
  { from: 1, to: 23, color: "crimson", width: 2 },
  { from: 1, to: 31 },
  { from: 2, to: 11, color: "gray" },
  { from: 2, to: 12, color: "olive", width: 2 },
  { from: 2, to: 13, color: "gray", dash: [3, 2] },
  { from: 2, to: 21, color: "crimson", width: 2 },
  { from: 2, to: 22, color: "crimson", width: 2 },
  { from: 2, to: 23, color: "black", width: 3 },
  { from: 2, to: 31, color: "black", dash: [3, 2] }
];
myDiagram.model = new go.GraphLinksModel(nodeDataArray, linkDataArray);
}
window.addEventListener('DOMContentLoaded', init);
</script>

<div id="sample">
<div id="myDiagramDiv" style="border: solid 1px black; width:100%; height:600px"></div>
<p> A sample of a Euler diagram: that is, a means of representing various sets and their relationships with one another. Euler diagrams have much in common with Venn diagrams.
This diagram is read-only, but clicking on a node will search Wikipedia
with a query string generated from the "text" property of the node data.
</p>
</div>
  </div>
  <!-- * * * * * * * * * * * * * -->
  <!--  End of GoJS sample code  -->
