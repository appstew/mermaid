```shell
[dami@fedora mermaid]$ git status
On branch develop
Your branch is up to date with 'origin/develop'.

Changes to be committed:
(use "git restore --staged <file>..." to unstage)
new file:   docs/section3/220902-1.png
new file:   docs/section3/220902.md
new file:   "docs/section3/\352\263\274\354\240\234\354\225\210\353\202\264.md"

Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
modified:   docs/_sidebar.md
modified:   docs/diary/index.md
modified:   docs/section3/index.md

Untracked files:
(use "git add <file>..." to include in what will be committed)
mermaid.iml
mermaid/

[dami@fedora mermaid]$ git add .
[dami@fedora mermaid]$ git commit -m 'md'
yarn run v1.22.17
$ lint-staged
✔ Preparing lint-staged...
❯ Running tasks for staged files...
❯ .lintstagedrc.json — 37 files
❯ *.{js,json,html,md} — 19 files
✖ yarn lint:fix [FAILED]
↓ Skipped because of errors from tasks. [SKIPPED]
✔ Reverting to original state because of errors...
✔ Cleaning up temporary files...

✖ yarn lint:fix:
error Command failed with exit code 1.
error Command failed with exit code 1.
$ yarn lint --fix /javatest/hrd/intelliJ_projects/repository/mermaid/docs/_sidebar.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/diary/index.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/220902.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/index.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/과제안내.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/404.html /javatest/hrdelliJ_projects/repository/mermaid/mermaid/doc/TOC.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/css.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/extend.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/faq.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/html.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/js.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/misc.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/usage.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/index.html /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/main.js /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/plugins.js /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/vendor/modernizr-3.11.2.min.js /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/package.json
$ eslint ./ --ext .js,.json,.html --fix /javatest/hrd/intelliJ_projects/repository/mermaid/docs/_sidebar.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/diary/index.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/220902.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/index.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/과제안내.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/html /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/TOC.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/css.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/extend.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/faq.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/html.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/js.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/misc.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/usage.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/index.html /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/main.js /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/plugins.js /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/vendor/modernizr-3.11.2.min.js /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/package.json

/javatest/hrd/intelliJ_projects/repository/mermaid/__mocks__/d3.js
2:3  warning  Missing JSDoc comment  jsdoc/require-jsdoc

/javatest/hrd/intelliJ_projects/repository/mermaid/cypress/platform/viewer.js
40:1  warning  Missing JSDoc @returns declaration          jsdoc/require-returns
41:1  warning  Missing JSDoc @param "current" description  jsdoc/require-param-description
41:1  warning  Missing JSDoc @param "current" type         jsdoc/require-param-type
42:1  warning  Missing JSDoc @param "update" description   jsdoc/require-param-description
42:1  warning  Missing JSDoc @param "update" type          jsdoc/require-param-type

/javatest/hrd/intelliJ_projects/repository/mermaid/docs/_sidebar.md
0:0  warning  File ignored because of a matching ignore pattern. Use "--no-ignore" to override

/javatest/hrd/intelliJ_projects/repository/mermaid/docs/diary/index.md
0:0  warning  File ignored because of a matching ignore pattern. Use "--no-ignore" to override

/javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/220902.md
0:0  warning  File ignored because of a matching ignore pattern. Use "--no-ignore" to override

/javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/index.md
0:0  warning  File ignored because of a matching ignore pattern. Use "--no-ignore" to override

/javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/과제안내.md
0:0  warning  File ignored because of a matching ignore pattern. Use "--no-ignore" to override

/javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/html.md
209:87  error  Unnecessary escape character: \/  no-useless-escape

/javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/vendor/modernizr-3.11.2.min.js
4:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
5:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
5:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
6:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
6:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
11:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
11:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
23:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
24:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
24:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
25:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
25:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
46:3   error    Delete `/**⏎···*⏎···*/⏎··`            prettier/prettier
46:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
56:3   error    Delete `/**⏎···*⏎···*/⏎··`            prettier/prettier
56:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
62:4   error    Delete `⏎··/**⏎···*⏎···*/`            prettier/prettier
63:3   warning  Missing JSDoc @param "e" declaration  jsdoc/require-param
63:3   warning  Missing JSDoc @param "t" declaration  jsdoc/require-param
63:3   warning  Missing JSDoc @param "r" declaration  jsdoc/require-param
63:3   warning  Missing JSDoc @param "o" declaration  jsdoc/require-param
63:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
97:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
98:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
98:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
99:1   warning  Missing JSDoc @param "n" description  jsdoc/require-param-description
99:1   warning  Missing JSDoc @param "n" type         jsdoc/require-param-type
100:1   warning  Missing JSDoc @param "r" description  jsdoc/require-param-description
100:1   warning  Missing JSDoc @param "r" type         jsdoc/require-param-type
118:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
119:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
119:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
120:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
120:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
125:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
125:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
125:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
133:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
134:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
134:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
135:1   warning  Missing JSDoc @param "n" description  jsdoc/require-param-description
135:1   warning  Missing JSDoc @param "n" type         jsdoc/require-param-type
154:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
154:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
154:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
162:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
163:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
163:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
164:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
164:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
165:1   warning  Missing JSDoc @param "n" description  jsdoc/require-param-description
165:1   warning  Missing JSDoc @param "n" type         jsdoc/require-param-type
166:1   warning  Missing JSDoc @param "i" description  jsdoc/require-param-description
166:1   warning  Missing JSDoc @param "i" type         jsdoc/require-param-type
169:5   warning  Missing JSDoc comment                 jsdoc/require-jsdoc
188:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
189:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
189:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
190:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
190:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
197:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
198:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
198:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
199:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
199:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
200:1   warning  Missing JSDoc @param "n" description  jsdoc/require-param-description
200:1   warning  Missing JSDoc @param "n" type         jsdoc/require-param-type
208:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
209:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
209:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
210:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
210:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
211:1   warning  Missing JSDoc @param "n" description  jsdoc/require-param-description
211:1   warning  Missing JSDoc @param "n" type         jsdoc/require-param-type
212:1   warning  Missing JSDoc @param "r" description  jsdoc/require-param-description
212:1   warning  Missing JSDoc @param "r" type         jsdoc/require-param-type
213:1   warning  Missing JSDoc @param "i" description  jsdoc/require-param-description
213:1   warning  Missing JSDoc @param "i" type         jsdoc/require-param-type
222:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
223:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
223:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
224:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
224:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
225:1   warning  Missing JSDoc @param "n" description  jsdoc/require-param-description
225:1   warning  Missing JSDoc @param "n" type         jsdoc/require-param-type
292:25  error    Delete `⏎····/**⏎·····*⏎·····*/`      prettier/prettier
293:5   warning  Missing JSDoc @param "e" declaration  jsdoc/require-param
293:5   warning  Missing JSDoc @param "n" declaration  jsdoc/require-param
293:5   warning  Missing JSDoc @returns declaration    jsdoc/require-returns

/javatest/hrd/intelliJ_projects/repository/mermaid/test.js
1:1  warning  Missing JSDoc comment  jsdoc/require-jsdoc

✖ 102 problems (5 errors, 97 warnings)
4 errors and 9 warnings potentially fixable with the `--fix` option.

info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
error Command failed with exit code 1.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
husky - pre-commit hook exited with code 1 (error)
[dami@fedora mermaid]$ clear
[dami@fedora mermaid]$ git commit -m 'md' > ./docs/diary commiterror.json
bash: ./docs/diary: Is a directory
[dami@fedora mermaid]$ git commit -m 'md' > ./docs/diary/commiterror.json
yarn run v1.22.17
$ lint-staged
✔ Preparing lint-staged...
❯ Running tasks for staged files...
❯ .lintstagedrc.json — 37 files
❯ *.{js,json,html,md} — 19 files
✖ yarn lint:fix [FAILED]
↓ Skipped because of errors from tasks. [SKIPPED]
✔ Reverting to original state because of errors...
✔ Cleaning up temporary files...

✖ yarn lint:fix:
error Command failed with exit code 1.
error Command failed with exit code 1.
$ yarn lint --fix /javatest/hrd/intelliJ_projects/repository/mermaid/docs/_sidebar.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/diary/index.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/220902.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/index.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/과제안내.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/404.html /javatest/hrdelliJ_projects/repository/mermaid/mermaid/doc/TOC.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/css.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/extend.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/faq.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/html.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/js.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/misc.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/usage.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/index.html /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/main.js /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/plugins.js /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/vendor/modernizr-3.11.2.min.js /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/package.json
$ eslint ./ --ext .js,.json,.html --fix /javatest/hrd/intelliJ_projects/repository/mermaid/docs/_sidebar.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/diary/index.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/220902.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/index.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/과제안내.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/html /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/TOC.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/css.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/extend.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/faq.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/html.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/js.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/misc.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/usage.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/index.html /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/main.js /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/plugins.js /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/vendor/modernizr-3.11.2.min.js /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/package.json

/javatest/hrd/intelliJ_projects/repository/mermaid/__mocks__/d3.js
2:3  warning  Missing JSDoc comment  jsdoc/require-jsdoc

/javatest/hrd/intelliJ_projects/repository/mermaid/cypress/platform/viewer.js
40:1  warning  Missing JSDoc @returns declaration          jsdoc/require-returns
41:1  warning  Missing JSDoc @param "current" description  jsdoc/require-param-description
41:1  warning  Missing JSDoc @param "current" type         jsdoc/require-param-type
42:1  warning  Missing JSDoc @param "update" description   jsdoc/require-param-description
42:1  warning  Missing JSDoc @param "update" type          jsdoc/require-param-type

/javatest/hrd/intelliJ_projects/repository/mermaid/docs/_sidebar.md
0:0  warning  File ignored because of a matching ignore pattern. Use "--no-ignore" to override

/javatest/hrd/intelliJ_projects/repository/mermaid/docs/diary/index.md
0:0  warning  File ignored because of a matching ignore pattern. Use "--no-ignore" to override

/javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/220902.md
0:0  warning  File ignored because of a matching ignore pattern. Use "--no-ignore" to override

/javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/index.md
0:0  warning  File ignored because of a matching ignore pattern. Use "--no-ignore" to override

/javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/과제안내.md
0:0  warning  File ignored because of a matching ignore pattern. Use "--no-ignore" to override

/javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/html.md
209:87  error  Unnecessary escape character: \/  no-useless-escape

/javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/vendor/modernizr-3.11.2.min.js
4:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
5:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
5:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
6:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
6:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
11:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
11:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
23:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
24:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
24:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
25:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
25:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
46:3   error    Delete `/**⏎···*⏎···*/⏎··`            prettier/prettier
46:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
56:3   error    Delete `/**⏎···*⏎···*/⏎··`            prettier/prettier
56:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
62:4   error    Delete `⏎··/**⏎···*⏎···*/`            prettier/prettier
63:3   warning  Missing JSDoc @param "e" declaration  jsdoc/require-param
63:3   warning  Missing JSDoc @param "t" declaration  jsdoc/require-param
63:3   warning  Missing JSDoc @param "r" declaration  jsdoc/require-param
63:3   warning  Missing JSDoc @param "o" declaration  jsdoc/require-param
63:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
97:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
98:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
98:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
99:1   warning  Missing JSDoc @param "n" description  jsdoc/require-param-description
99:1   warning  Missing JSDoc @param "n" type         jsdoc/require-param-type
100:1   warning  Missing JSDoc @param "r" description  jsdoc/require-param-description
100:1   warning  Missing JSDoc @param "r" type         jsdoc/require-param-type
118:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
119:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
119:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
120:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
120:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
125:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
125:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
125:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
133:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
134:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
134:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
135:1   warning  Missing JSDoc @param "n" description  jsdoc/require-param-description
135:1   warning  Missing JSDoc @param "n" type         jsdoc/require-param-type
154:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
154:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
154:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
162:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
163:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
163:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
164:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
164:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
165:1   warning  Missing JSDoc @param "n" description  jsdoc/require-param-description
165:1   warning  Missing JSDoc @param "n" type         jsdoc/require-param-type
166:1   warning  Missing JSDoc @param "i" description  jsdoc/require-param-description
166:1   warning  Missing JSDoc @param "i" type         jsdoc/require-param-type
169:5   warning  Missing JSDoc comment                 jsdoc/require-jsdoc
188:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
189:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
189:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
190:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
190:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
197:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
198:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
198:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
199:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
199:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
200:1   warning  Missing JSDoc @param "n" description  jsdoc/require-param-description
200:1   warning  Missing JSDoc @param "n" type         jsdoc/require-param-type
208:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
209:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
209:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
210:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
210:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
211:1   warning  Missing JSDoc @param "n" description  jsdoc/require-param-description
211:1   warning  Missing JSDoc @param "n" type         jsdoc/require-param-type
212:1   warning  Missing JSDoc @param "r" description  jsdoc/require-param-description
212:1   warning  Missing JSDoc @param "r" type         jsdoc/require-param-type
213:1   warning  Missing JSDoc @param "i" description  jsdoc/require-param-description
213:1   warning  Missing JSDoc @param "i" type         jsdoc/require-param-type
222:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
223:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
223:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
224:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
224:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
225:1   warning  Missing JSDoc @param "n" description  jsdoc/require-param-description
225:1   warning  Missing JSDoc @param "n" type         jsdoc/require-param-type
292:25  error    Delete `⏎····/**⏎·····*⏎·····*/`      prettier/prettier
293:5   warning  Missing JSDoc @param "e" declaration  jsdoc/require-param
293:5   warning  Missing JSDoc @param "n" declaration  jsdoc/require-param
293:5   warning  Missing JSDoc @returns declaration    jsdoc/require-returns

/javatest/hrd/intelliJ_projects/repository/mermaid/test.js
1:1  warning  Missing JSDoc comment  jsdoc/require-jsdoc

✖ 102 problems (5 errors, 97 warnings)
4 errors and 9 warnings potentially fixable with the `--fix` option.

info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
error Command failed with exit code 1.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
husky - pre-commit hook exited with code 1 (error)
[dami@fedora mermaid]$ clear
[dami@fedora mermaid]$ git commit -m 'md' > ./docs/diary/commiterror.md
yarn run v1.22.17
$ lint-staged
✔ Preparing lint-staged...
❯ Running tasks for staged files...
❯ .lintstagedrc.json — 37 files
❯ *.{js,json,html,md} — 19 files
✖ yarn lint:fix [FAILED]
↓ Skipped because of errors from tasks. [SKIPPED]
✔ Reverting to original state because of errors...
✔ Cleaning up temporary files...

✖ yarn lint:fix:
error Command failed with exit code 1.
error Command failed with exit code 1.
$ yarn lint --fix /javatest/hrd/intelliJ_projects/repository/mermaid/docs/_sidebar.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/diary/index.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/220902.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/index.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/과제안내.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/404.html /javatest/hrdelliJ_projects/repository/mermaid/mermaid/doc/TOC.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/css.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/extend.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/faq.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/html.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/js.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/misc.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/usage.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/index.html /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/main.js /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/plugins.js /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/vendor/modernizr-3.11.2.min.js /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/package.json
$ eslint ./ --ext .js,.json,.html --fix /javatest/hrd/intelliJ_projects/repository/mermaid/docs/_sidebar.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/diary/index.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/220902.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/index.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/과제안내.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/html /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/TOC.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/css.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/extend.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/faq.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/html.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/js.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/misc.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/usage.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/index.html /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/main.js /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/plugins.js /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/vendor/modernizr-3.11.2.min.js /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/package.json

/javatest/hrd/intelliJ_projects/repository/mermaid/__mocks__/d3.js
2:3  warning  Missing JSDoc comment  jsdoc/require-jsdoc

/javatest/hrd/intelliJ_projects/repository/mermaid/cypress/platform/viewer.js
40:1  warning  Missing JSDoc @returns declaration          jsdoc/require-returns
41:1  warning  Missing JSDoc @param "current" description  jsdoc/require-param-description
41:1  warning  Missing JSDoc @param "current" type         jsdoc/require-param-type
42:1  warning  Missing JSDoc @param "update" description   jsdoc/require-param-description
42:1  warning  Missing JSDoc @param "update" type          jsdoc/require-param-type

/javatest/hrd/intelliJ_projects/repository/mermaid/docs/_sidebar.md
0:0  warning  File ignored because of a matching ignore pattern. Use "--no-ignore" to override

/javatest/hrd/intelliJ_projects/repository/mermaid/docs/diary/index.md
0:0  warning  File ignored because of a matching ignore pattern. Use "--no-ignore" to override

/javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/220902.md
0:0  warning  File ignored because of a matching ignore pattern. Use "--no-ignore" to override

/javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/index.md
0:0  warning  File ignored because of a matching ignore pattern. Use "--no-ignore" to override

/javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/과제안내.md
0:0  warning  File ignored because of a matching ignore pattern. Use "--no-ignore" to override

/javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/html.md
209:87  error  Unnecessary escape character: \/  no-useless-escape

/javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/vendor/modernizr-3.11.2.min.js
4:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
5:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
5:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
6:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
6:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
11:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
11:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
23:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
24:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
24:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
25:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
25:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
46:3   error    Delete `/**⏎···*⏎···*/⏎··`            prettier/prettier
46:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
56:3   error    Delete `/**⏎···*⏎···*/⏎··`            prettier/prettier
56:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
62:4   error    Delete `⏎··/**⏎···*⏎···*/`            prettier/prettier
63:3   warning  Missing JSDoc @param "e" declaration  jsdoc/require-param
63:3   warning  Missing JSDoc @param "t" declaration  jsdoc/require-param
63:3   warning  Missing JSDoc @param "r" declaration  jsdoc/require-param
63:3   warning  Missing JSDoc @param "o" declaration  jsdoc/require-param
63:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
97:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
98:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
98:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
99:1   warning  Missing JSDoc @param "n" description  jsdoc/require-param-description
99:1   warning  Missing JSDoc @param "n" type         jsdoc/require-param-type
100:1   warning  Missing JSDoc @param "r" description  jsdoc/require-param-description
100:1   warning  Missing JSDoc @param "r" type         jsdoc/require-param-type
118:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
119:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
119:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
120:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
120:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
125:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
125:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
125:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
133:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
134:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
134:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
135:1   warning  Missing JSDoc @param "n" description  jsdoc/require-param-description
135:1   warning  Missing JSDoc @param "n" type         jsdoc/require-param-type
154:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
154:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
154:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
162:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
163:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
163:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
164:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
164:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
165:1   warning  Missing JSDoc @param "n" description  jsdoc/require-param-description
165:1   warning  Missing JSDoc @param "n" type         jsdoc/require-param-type
166:1   warning  Missing JSDoc @param "i" description  jsdoc/require-param-description
166:1   warning  Missing JSDoc @param "i" type         jsdoc/require-param-type
169:5   warning  Missing JSDoc comment                 jsdoc/require-jsdoc
188:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
189:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
189:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
190:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
190:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
197:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
198:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
198:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
199:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
199:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
200:1   warning  Missing JSDoc @param "n" description  jsdoc/require-param-description
200:1   warning  Missing JSDoc @param "n" type         jsdoc/require-param-type
208:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
209:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
209:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
210:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
210:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
211:1   warning  Missing JSDoc @param "n" description  jsdoc/require-param-description
211:1   warning  Missing JSDoc @param "n" type         jsdoc/require-param-type
212:1   warning  Missing JSDoc @param "r" description  jsdoc/require-param-description
212:1   warning  Missing JSDoc @param "r" type         jsdoc/require-param-type
213:1   warning  Missing JSDoc @param "i" description  jsdoc/require-param-description
213:1   warning  Missing JSDoc @param "i" type         jsdoc/require-param-type
222:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
223:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
223:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
224:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
224:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
225:1   warning  Missing JSDoc @param "n" description  jsdoc/require-param-description
225:1   warning  Missing JSDoc @param "n" type         jsdoc/require-param-type
292:25  error    Delete `⏎····/**⏎·····*⏎·····*/`      prettier/prettier
293:5   warning  Missing JSDoc @param "e" declaration  jsdoc/require-param
293:5   warning  Missing JSDoc @param "n" declaration  jsdoc/require-param
293:5   warning  Missing JSDoc @returns declaration    jsdoc/require-returns

/javatest/hrd/intelliJ_projects/repository/mermaid/test.js
1:1  warning  Missing JSDoc comment  jsdoc/require-jsdoc

✖ 102 problems (5 errors, 97 warnings)
4 errors and 9 warnings potentially fixable with the `--fix` option.

info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
error Command failed with exit code 1.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
husky - pre-commit hook exited with code 1 (error)
[dami@fedora mermaid]$ lsof -i > ./docs/diary/test.md
[dami@fedora mermaid]$ git commit -m 'md' &> ./docs/diary/commiterror.md
[dami@fedora mermaid]$ git commit -m 'md' &> ./docs/diary/commiterror.json
[dami@fedora mermaid]$ git commit -m 'md' &> ./docs/diary/commiterror.txt
[dami@fedora mermaid]$ clear
[dami@fedora mermaid]$ git commit -m 'md'
yarn run v1.22.17
$ lint-staged
✔ Preparing lint-staged...
✔ Hiding unstaged changes to partially staged files...
❯ Running tasks for staged files...
❯ .lintstagedrc.json — 39 files
❯ *.{js,json,html,md} — 21 files
✖ yarn lint:fix [FAILED]
↓ Skipped because of errors from tasks. [SKIPPED]
↓ Skipped because of errors from tasks. [SKIPPED]
✔ Reverting to original state because of errors...
✔ Cleaning up temporary files...

✖ yarn lint:fix:
error Command failed with exit code 1.
error Command failed with exit code 1.
$ yarn lint --fix /javatest/hrd/intelliJ_projects/repository/mermaid/docs/_sidebar.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/diary/commiterror.json /javatest/hrd/intelliJ_projects/repository/mermaid/docs/diary/commiterror.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/diary/index.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/220902.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/index.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/과제안내.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/404.html /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/TOC.md /javatest/hrd/intelprojects/repository/mermaid/mermaid/doc/css.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/extend.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/faq.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/html.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/js.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/misc.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/usage.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/index.html /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/main.js /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/plugins.js /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/vendor/modernizr-3.11.2.min.js /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/package.json
$ eslint ./ --ext .js,.json,.html --fix /javatest/hrd/intelliJ_projects/repository/mermaid/docs/_sidebar.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/diary/commiterror.json /javatest/hrd/intelliJ_projects/repository/mermaid/docs/diary/commiterror.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/diary/index.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/220902.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/index.md /javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/과제안내.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/404.html /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/TOC.javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/css.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/extend.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/faq.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/html.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/js.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/misc.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/usage.md /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/index.html /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/main.js /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/plugins.js /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/vendor/modernizr-3.11.2.min.js /javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/package.json

/javatest/hrd/intelliJ_projects/repository/mermaid/__mocks__/d3.js
2:3  warning  Missing JSDoc comment  jsdoc/require-jsdoc

/javatest/hrd/intelliJ_projects/repository/mermaid/cypress/platform/viewer.js
40:1  warning  Missing JSDoc @returns declaration          jsdoc/require-returns
41:1  warning  Missing JSDoc @param "current" description  jsdoc/require-param-description
41:1  warning  Missing JSDoc @param "current" type         jsdoc/require-param-type
42:1  warning  Missing JSDoc @param "update" description   jsdoc/require-param-description
42:1  warning  Missing JSDoc @param "update" type          jsdoc/require-param-type

/javatest/hrd/intelliJ_projects/repository/mermaid/docs/_sidebar.md
0:0  warning  File ignored because of a matching ignore pattern. Use "--no-ignore" to override

/javatest/hrd/intelliJ_projects/repository/mermaid/docs/diary/commiterror.json
0:0  warning  File ignored because of a matching ignore pattern. Use "--no-ignore" to override

/javatest/hrd/intelliJ_projects/repository/mermaid/docs/diary/commiterror.md
0:0  warning  File ignored because of a matching ignore pattern. Use "--no-ignore" to override

/javatest/hrd/intelliJ_projects/repository/mermaid/docs/diary/index.md
0:0  warning  File ignored because of a matching ignore pattern. Use "--no-ignore" to override

/javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/220902.md
0:0  warning  File ignored because of a matching ignore pattern. Use "--no-ignore" to override

/javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/index.md
0:0  warning  File ignored because of a matching ignore pattern. Use "--no-ignore" to override

/javatest/hrd/intelliJ_projects/repository/mermaid/docs/section3/과제안내.md
0:0  warning  File ignored because of a matching ignore pattern. Use "--no-ignore" to override

/javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/doc/html.md
209:87  error  Unnecessary escape character: \/  no-useless-escape

/javatest/hrd/intelliJ_projects/repository/mermaid/mermaid/js/vendor/modernizr-3.11.2.min.js
4:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
5:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
5:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
6:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
6:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
11:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
11:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
23:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
24:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
24:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
25:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
25:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
46:3   error    Delete `/**⏎···*⏎···*/⏎··`            prettier/prettier
46:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
56:3   error    Delete `/**⏎···*⏎···*/⏎··`            prettier/prettier
56:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
62:4   error    Delete `⏎··/**⏎···*⏎···*/`            prettier/prettier
63:3   warning  Missing JSDoc @param "e" declaration  jsdoc/require-param
63:3   warning  Missing JSDoc @param "t" declaration  jsdoc/require-param
63:3   warning  Missing JSDoc @param "r" declaration  jsdoc/require-param
63:3   warning  Missing JSDoc @param "o" declaration  jsdoc/require-param
63:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
97:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
98:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
98:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
99:1   warning  Missing JSDoc @param "n" description  jsdoc/require-param-description
99:1   warning  Missing JSDoc @param "n" type         jsdoc/require-param-type
100:1   warning  Missing JSDoc @param "r" description  jsdoc/require-param-description
100:1   warning  Missing JSDoc @param "r" type         jsdoc/require-param-type
118:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
119:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
119:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
120:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
120:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
125:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
125:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
125:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
133:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
134:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
134:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
135:1   warning  Missing JSDoc @param "n" description  jsdoc/require-param-description
135:1   warning  Missing JSDoc @param "n" type         jsdoc/require-param-type
154:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
154:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
154:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
162:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
163:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
163:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
164:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
164:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
165:1   warning  Missing JSDoc @param "n" description  jsdoc/require-param-description
165:1   warning  Missing JSDoc @param "n" type         jsdoc/require-param-type
166:1   warning  Missing JSDoc @param "i" description  jsdoc/require-param-description
166:1   warning  Missing JSDoc @param "i" type         jsdoc/require-param-type
169:5   warning  Missing JSDoc comment                 jsdoc/require-jsdoc
188:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
189:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
189:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
190:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
190:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
197:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
198:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
198:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
199:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
199:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
200:1   warning  Missing JSDoc @param "n" description  jsdoc/require-param-description
200:1   warning  Missing JSDoc @param "n" type         jsdoc/require-param-type
208:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
209:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
209:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
210:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
210:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
211:1   warning  Missing JSDoc @param "n" description  jsdoc/require-param-description
211:1   warning  Missing JSDoc @param "n" type         jsdoc/require-param-type
212:1   warning  Missing JSDoc @param "r" description  jsdoc/require-param-description
212:1   warning  Missing JSDoc @param "r" type         jsdoc/require-param-type
213:1   warning  Missing JSDoc @param "i" description  jsdoc/require-param-description
213:1   warning  Missing JSDoc @param "i" type         jsdoc/require-param-type
222:3   warning  Missing JSDoc @returns declaration    jsdoc/require-returns
223:1   warning  Missing JSDoc @param "e" description  jsdoc/require-param-description
223:1   warning  Missing JSDoc @param "e" type         jsdoc/require-param-type
224:1   warning  Missing JSDoc @param "t" description  jsdoc/require-param-description
224:1   warning  Missing JSDoc @param "t" type         jsdoc/require-param-type
225:1   warning  Missing JSDoc @param "n" description  jsdoc/require-param-description
225:1   warning  Missing JSDoc @param "n" type         jsdoc/require-param-type
292:25  error    Delete `⏎····/**⏎·····*⏎·····*/`      prettier/prettier
293:5   warning  Missing JSDoc @param "e" declaration  jsdoc/require-param
293:5   warning  Missing JSDoc @param "n" declaration  jsdoc/require-param
293:5   warning  Missing JSDoc @returns declaration    jsdoc/require-returns

/javatest/hrd/intelliJ_projects/repository/mermaid/test.js
1:1  warning  Missing JSDoc comment  jsdoc/require-jsdoc

✖ 104 problems (5 errors, 99 warnings)
4 errors and 9 warnings potentially fixable with the `--fix` option.

info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
error Command failed with exit code 1.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
husky - pre-commit hook exited with code 1 (error)
[dami@fedora mermaid]$
```
