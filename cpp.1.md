
	//endl boş satır bırakır
	//65 "A"nın desimal değeridir- bu ifadenin sonucu A'dır
	
	/*
	char deger = 65;
	string isim, soyisim;
	int en, boy;
	cout << "Isim ve soyisim giriniz : "<<endl;
	cin >> isim >> soyisim;
	cout << "Adiniz : " << isim << soyisim;
	*/

	//	int x = floor(2.7);
	//cout << x;

	//switch(sayi)
	//	{
	//	case 1:
	//		cout << "sayı ";
	//		break;
	// 
	//	case 2:
	//		cout << "sayı ";
	//		break;
	// 
	//	default:
	//		cout << "def ";
	//		break;
	//	}
	string deneme;
	int s1,s2,s3,passwordInput , password = 1234 ;

	//eleman sayısı içeri yazıldı
	
	//eleman atamaları veya döngüyle girdi alınır
	
	int dizi[2][2] = {{12,23} ,{43,42}};
	s1 = pow(2, 5);
	cout << s1;
	
	cout << "enter your password : " << endl;

	cin >> passwordInput;
	cout << endl;

	if (password == passwordInput) {
		cout << "your password is correct."<<endl;
	}
	else {
		cout << "you entered wrong password";
	}
	cout << endl;
	bool ctrl = true;
	if (ctrl) {
		cout << "sayi giriniz";
		cin >> s1;
		if(s1==10){
			ctrl = false;
		}																					
		cout	<< "devamke";	
	}
	else {
		cout << "pompake";
	}
	ctrl = true;
	while (ctrl) {
		cin >> deneme;
		if (deneme== "1234") {
			ctrl = false;
		}
	}
	cout << endl;
	return 0;
