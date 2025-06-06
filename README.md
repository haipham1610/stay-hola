# StayHola
## Introduction
StayHola là ứng dụng Android giúp người dùng tìm và thuê phòng trọ tại Hòa Lạc một cách dễ dàng. Ứng dụng hướng đến đối tượng chính là sinh viên và người trẻ, cung cấp các tính năng như tìm kiếm phòng theo vị trí, giá cả, đặt phòng, và liên hệ với chủ trọ.

## Hướng dẫn cài đặt

1. Clone repository:git clone https://github.com/haipham1610/stay-hola.git

2. Mở dự án: Mở thư mục StayHola trong Android Studio.
3. Cấu hình môi trường:
 - Đảm bảo cài đặt Android SDK (API 21 trở lên).
 - Đồng bộ Gradle trong Android Studio (File > Sync Project with Gradle Files).

## Git flow
Nếu chưa tạo branch, (code tính năng mới):
- B1: Tạo branch.

Nếu đang code dở, mà qua lười code để nay code nốt:
- B2: Open git bash or cmd trong project
- B3: run command ``` git checkout dev ``` để chuyển về nhánh dev
- B4: run command ``` git pull ``` để pull code mới nhất về (quan trọng để tránh bị conflict)
- B5: run command ``` git checkout <your_branch> ``` để chuyển sang branch của mình
- B6.1: run command ``` git merge dev ``` để merge code mới nhất trên dev
- B6.2: nếu ae bị conflict ở đây thì xem xem code nào ko phải của mình thì accept code mới nhé. Còn code mình đang dev thì accept my code (để tránh bị mất code người khác)
- B7: code thoii!
- B8: run command ``` git add . ``` để push code lên git local
- B9: run command: ``` git commit -m" <commit_cua_minh> " ``` để commit
- B10: run command: ``` git push ``` để push code lên git global
- B11: Mở project trên github, chuyển sang branch của mình
- B12: Tạo Merge Request
- B13: nếu không bị conflict thì merge thôi:
       nhớ bỏ chọn 'Delete source branch when merge request is accepted.' để không bị xóa branch, phòng trường hợp có bug thì fix lại trên branch đó
       và chọn 'Squash commits when merge request is accepted.' để squash nhiều commits lại thành 1 commit khi merge vào dev để nếu có bug thì rollback lại version cũ dễ


## Authors
- **Development Team**: TEAM 3 - PRM392
- **Contact**: vcl@gmail.com


