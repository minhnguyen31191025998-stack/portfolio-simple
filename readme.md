//git command

Mở folder muốn đẩy lên github
Mở terminal (cmd + J)
git init
git add -A
git commit -m "initial commit" (cho commit đầu tiên) => message tùy theo nội dung mà mình thay đổi trong code
Tạo repo trên github => muốn deploy vercel thì để public
git remote add origin ...... (link là địa chỉ của repo github)
git push --set-upstream origin master (chỉ làm lần đầu khi đẩy lên github) lần sau => git push
Kiểm tra lại github xem có file code chưa? nếu có => thành công
Để deploy thì xài vercel
Đăng nhập bằng github => new project => import repo github vừa tạo
Deploy => có link deploy => xong
