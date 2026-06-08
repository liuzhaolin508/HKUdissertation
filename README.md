# HKU Dissertation Project

This repository is the collaboration entry point for the HKU dissertation project stored locally at `D:\Codex Projects\HKUdissertation\毕业设计`.

The project is a vision-tactile robotic gripper system based on the 9DTact photometric stereo tactile sensing pipeline. It combines Raspberry Pi 4B, OV5640 camera input, OpenCV image processing, lightweight deep learning models, ROS1/PWM control, and mechanical gripper hardware for stable grasping of unknown or fragile objects.

## Local Project Layout

- `00_项目说明/`: project handover notes, background, plan, and file organization.
- `01_当前代码_code/9DTact_code/`: current Python, ROS, shape reconstruction, and force estimation code.
- `02_硬件与3D模型_hardware/`: SolidWorks models, tactile sensor/gripper hardware assets, and demo videos.
- `03_会议与汇报_docs/`: progress reports, figures, and presentation scripts.
- `04_采购报销与BOM_admin/`: BOM, purchasing, and reimbursement documents.
- `05_参考资料_reference/`: external references, gripper downloads, sensor and robotic-arm materials.
- `90_历史备份_archive/`: historical zip archives, Linux backup materials, old code, and model backups.

## Upload Notes

The local project currently contains about 564 files and roughly 914 MB of material. Several files exceed GitHub's normal single-file limit, including external reference archives and trained model weights. Those files should be kept local or moved to Git LFS/cloud storage before a full binary upload.

This repository is prepared so the GitHub link can be shared with ChatGPT/Codex for project discussion, planning, and code review. A complete Git push should be done later with Git + GitHub CLI + Git LFS.
