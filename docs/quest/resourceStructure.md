# resourceStructure
| device  | partition1 | partition2 | partition3 | partition4 |
| ---- | - | ------------------------------------ | -- | -- |
| nvme0n1    | /boot/efi |   grub2fedora | kvm.fedora | java.fedora |
| 어떤 리눅스, kvm 머신을 실행하든 같은 dir 에 마운트 |
| nvme1n1 /2TB | images qemukvm.files images/resources/javatest.img |
| loop0p2 /javatest | hrd obsidian certificate blog .. |  |

- sandisk32GB 에서 클론질라 실행 후 / nvme0n1 > wd4tb 로 partclone
- nvme1n1 > wd4tb 로 raw copy
-
