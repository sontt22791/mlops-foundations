## Bash Essentials for Cloud
https://www.youtube.com/watch?v=5_Oqp7ksChU&t=6s

```
ls -la => list all
cd => return HOME
cd / => return root
ctr+l => clear

history => xem lai lich su cac command
!30 => run lai command thu 30 trong history => thuong dung trong truong hop cau lenh dai

touch file => tao 1 file moi rong~
cat file => xem file do
nano file => edit
mv file1 file2 => rename file1 sang file2

vim file => edit file
	trong khi su dung vim: bam i hoac 1 phim bat ki de bat dau insert
	edit xong bam esc de thoat insert
	:wq de force quit
	neu bam nham ctrl+s thi bam ctr+q de thoat trang thai nay (sau khi bam ctrl+s thi van go dc chu nhung no ko hien)
	dd => xoa line (con tro fai o cuoi dong hoac dau dong)
	:q, :q! => quit ma ko save 
```


## BASH script
```
echo $SHELL => print ra bien SHELL
touch hello.sh => create file hello.sh

cau truc file hello.sh:
#!/usr/bin/env bash => required
bash script 1 (vd echo "helloworld")
bash script 2 (vd ls, pwd,....)

run file hello.sh:
chmod +x hello.sh (fai run cai nay truoc khi ./hello.sh)  use the chmod command to set the executable flag to make this script executable
./hello.sh (phai co ./ o truoc)
```

vd2:
```
#!/usr/bin/env python3 
=> có thể add thêm line này để khai báo sẽ sử dụng python3 
=> sau đó chmod +x add.py 
=> ./add.py để chạy file add.py (như cách run file hello.sh ở trên)
```

## Customize terminal
```
~/.bashrc => customize terminal
source ~/.bashrc => apply nhung cai vua customize o .bashrc

tao venv python: => dat ten la .venv de ko lam xao tron folder

which COMMAND => 

echo "text" => in ra text
wc => theo minh hieu la count:
	wc -l => count line
	wc -w => count words
	wc -c => count character
```

tham khảo: https://github.com/noahgift/cloud-bash-essentials