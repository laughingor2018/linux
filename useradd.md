创建不能登录的用户
sudo adduser nouser --system

创建不能登录的用户，登录需要提示输密码
sudo adduser nouser --shell=/bin/false 


创建不能登录且不创建用户目录
sudo adduser nouser --system --no-create-home
