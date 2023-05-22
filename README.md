# Belajar-GIT
Pengenalan GIT
GIT adalah salah satu version control system yang diciptakan oleh Linus Torvalds. GIT mencatat setiap perubahan file di code atau sourcode kita. GIT bisa menyimpan seluruh versi source code, berkolaborasi membangun sistem jadi mudah, dan berkontribusi di proyek open source
Memudahkan dalam tracking perubahan, memahami cara deploy modern, Dsb. GIT sangat dibutuhkan saat ingin membangun sistem dengan berkolaborasi, membuat versi dari sistem, backup sour code, dan berkolaborasi dengan programmer dunia

branch
1.git branch namabranch :membuat branch
2.git checkout namabranch :memindah branch=untuk pindah branch master>git checkout master
3.git commit -a -m "keterangan commit"/git commit -am " keterangan commit" :untuk commit file yang sudah modified
4.git branch :untuk menampilkan branch
5.git log  --all --decorate --oneline --graph :menampilkan visualisasi branch dalam bentuk graph/untuk merge file yang tidakbisa di merge langsung
=short>alias graph="git log --all --decorate --oneline --graph">graph
git merge namabranch :untuk merge file
git branch --merged :menampilkan branch yang sudah di merge
git branch -d namabranch :menghapus branch yang sudah di merge
git branch -D namabranh :menghapus file yang belum dimerge


