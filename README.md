# Belajar-GIT
1. Pengenalan GIT
    GIT adalah salah satu version control system yang diciptakan oleh Linus Torvalds. GIT mencatat setiap perubahan file di code atau sourcode kita. GIT bisa menyimpan seluruh versi source code, berkolaborasi membangun sistem jadi mudah, dan berkontribusi di proyek open source, memudahkan dalam tracking perubahan, memahami cara deploy modern, Dsb. GIT sangat dibutuhkan saat ingin membangun sistem dengan berkolaborasi, membuat versi dari sistem, backup sour code, dan berkolaborasi dengan programmer dunia.

2. Struktur dasar GIT
    Perintah-perintah dasar yang sering digunakan untuk mengoperasikan GIT
    a. git --version :menampilkan versi GIT
	b. git init :membuat file menjadi repo
	c. git add :  =untuk memasukkan file kedalam staging area, jika filenya banyak bisa menggunakan perintah   ->git add . 
	d. git status :untuk mengetahui status file, biasanya status file ada 3: unstaging (untracked),staging, modified
	e. git commit -m "keterangan commit" :untuk melakukan commit file =jika filenya 1 ->git commit -m file yang ingin di commit 
	f. git config : -Konfigurasi email dan username
                    -Biasanya disamakan dengan akun gitlab / github
                    -Config global untuk konfigurasi ke server
                    -Config local untuk konfigurasi local
                    -Untuk melihat semua konfigurasi yang ada di git bisa menggunakan perintah  git config --list
	g. git branch :membuat branch
	h. git help :untuk mencari perintah
	i. clear :untuk membersihkan GIT
	j. pwd(print working directory) :menunjukkan posisi directory
	k. ls :mengetahui isi folder yang ada di directory
	l. cd nama_directory:memindah directory
	m. esc>:q! :untuk keluar dari vim
	n. git log :untuk melihat semua perubahan/commit, untuk keluar dari log tekan q
    o. git clone :mengcopy repo dari server
    p. git remote :semacam API untuk berinteraksi antara clien dengan server
    q. git push :untuk mengirim commit ke server
    r. git pull :untuk mengambil commit dari server jika ada perubahan di server yang dibuat oleh branch lain yang commit

3. Branch
    a. git branch :untuk menampilkan semua branch (lokal)
    b. git branch --all :untuk menampilkan semua branch (publik)
    c. git branch nama_branch :membuat branch
    d. git checkout nama_branch :untuk berpindah branch, untuk pindah branch master> git checkout master
    e. git commit -a -m "keterangan commit"/git commit -am " keterangan commit" :untuk commit file yang sudah modified
    f. git log  --all --decorate --oneline --graph :menampilkan visualisasi branch dalam bentuk graph/untuk merge file yang tidak bisa di merge langsung, short>alias graph="git log --all --decorate --oneline --graph">graph
    g. git merge namabranch :untuk merge file
    h. git branch --merged :menampilkan branch yang sudah di merge
    i. git branch -d namabranch :menghapus branch yang sudah di merge
    j. git branch -D namabranh :menghapus file yang belum maupun sudah dimerge

4. Sourcetree
    Sourcetree merupakan Software berbasis GUI untuk memudahkan dalam mengoperasikan git, sourcetree sangat mudah digunakan, dalam menyelesaikan konflik menjadi lebih mudah, dan mempercepat pekerjaan dengan tampilan menu
