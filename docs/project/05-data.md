# Project Data

## 1. Domain Entities & Semantic Definitions

- **Super User:**
  - Name: Fixed "Super Admin"
  - Profile picture: Fixed [image](https://static.vecteezy.com/system/resources/thumbnails/012/210/707/small/worker-employee-businessman-avatar-profile-icon-vector.jpg)
  - Credentials: For login
- **Admin user:**
  - Name: Dynamic set by `Super Admin`
  - Profile picture: Default [image](https://img.magnific.com/free-vector/user-circles-set_78370-4704.jpg?semt=ais_hybrid&w=740&q=80), could also be updated by admin afterwards
  - Credentials: For login
- **Standard User:**
  - Name: Personal Name
  - Profile picture: From [image1](https://i.pinimg.com/736x/ce/af/fa/ceaffafb883c6a7b771cbbc50cbda07e.jpg), [image2](https://i.pinimg.com/474x/25/06/12/250612b1ec3cef69b64d7aea934e0bb2.jpg), [image3](https://i.pinimg.com/474x/b8/f2/6e/b8f26e64f85779231ae8a9db73110113.jpg), [image4](https://i.pinimg.com/474x/48/9d/40/489d40a44df35000d904592535a524e6.jpg) or uploaded by user
  - Credentials: For login
- **Discussion:**
  - Question: a clear question to be debated
  - Opening statement: a statement from moderator
  - Evidences: if author want to present any reference or file
  - Options: possible options to select for debaters or allowing custom option
  - Thumbnail: From [image1](https://i.pinimg.com/474x/6d/e9/1c/6de91c11a6c674a79cf315fe1929c135.jpg), [image2](https://png.pngtree.com/thumb_back/fh260/background/20220525/pngtree-tribune-realistic-debate-composition-image_1383404.jpg), [image3](https://static.vecteezy.com/system/resources/thumbnails/070/024/303/small/two-podiums-with-microphones-on-a-stage-free-photo.jpg), [image4](https://t4.ftcdn.net/jpg/10/32/21/17/360_F_1032211788_UDk4m37gQjZ1bjQaFSh15HTjWSMWCNw2.jpg) or moderator upload
- **Comment:**
  - Supporting Option: Each comment must be associated with one of options moderator has provided, debater can write custom if custom is allowed.
  - Statement/Content: text of the comment
  - Evidence: Any file or reference debater wants to attach

## 2. Entity Relationships
1. Standard user `start` debate
2. Standard user `make` comment `in` debate

## 3. Data Semantics & Invariants
1. No data should be deleted completely from the system