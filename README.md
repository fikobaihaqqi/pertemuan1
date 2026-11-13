# pertemuan1


void main() {

  print("Halo der");
  
  print('Hihu');
  
  String? yourUsername = "koyy";
  
  print(yourUsername);
  
  int yourAge = 20;
  
  print(yourAge); 
  

  //   Nilai ini tidak di rubah jika sudah di definisikan

  /*
   * nilai ini tidak di rubah
   * jika sudah di definisikan sebagai int
   * 
   * 
   * 
   * */
  //    jumlah = 22.8;
  //    print (yourAge);

  yourUsername = null;
  
  print(yourUsername);

  String? alamat;
  
  alamat = "";

  alamat = null;

  String alamatSaya = alamat ?? 'Bukan Dari solo';
  
  print(alamatSaya);

  //   Final
  
  final String yourNim = '1124160223';
  
  print(yourNim);

  // Const
  
  const String yourKampus = "Global Institute";
  
  print(yourKampus);

  //   Late Modifier
  
  late String myUsername;

  void setUsername() {
    myUsername = "Fiko baihaqqi";
    
    print(setUsername);
  }

  //   Type Data
  
  //   String
  
  String namaSaya = 'Fiko';
  
  String namaProdi = 'Teknik Informatika';
  
  print('Nama saya $namaSaya, Asal Prodi $namaProdi');

  //   Integer
  
  int hargaApel = 15000;
  
  int jumlahApel = 10;
  
  int totalHarga = hargaApel * jumlahApel;

  print('Total Harga: $totalHarga');

  // Double
  
  double nilaiMTK = 90.5;
  
  double nilaiIPA = 85.7;
  
  double nilaiAgama = 89.8;

  print(nilaiMTK + nilaiIPA + nilaiAgama);

  // Num
  
  num rating = 4;
  
  print(rating);

  rating = 4.7;
  
  print(rating);

  // Bool
  
  bool umurCukup = true;
  
  bool memilikiKTP = false;

  bool bolehMasuk = umurCukup && memilikiKTP;

  print(bolehMasuk);

  // List
  
  List<String> buah = ['Mangga', 'Jeruk Bali', 'Mengkudu', 'Lontar'];
  
  print(buah[1] + " " + "dan" + " " + buah[2]);

  buah.add("Pisang Jawa");

  print("Ini adalah : " + " " + buah[4]);

  // Set
  
  Set<String> nimMahasigma = {'1124160223', '1124160223', '1124160223'};
  
  print(nimMahasigma);
  
  //   Jadi kalau set itu bedanya sama list data tidak bisa duplikat jika sudah ada 1 maka tidak bisa ditambahkan lagi.

  // Map
  
  Map<String, dynamic> karyawanPTXYZ = {
    'id': 1,
    'nik': 'MSH001',
    'nama': 'FIKO BAIHAQQI',
    'jabatan': 'CYBER SECURITTY',
    'bagian': 'IT',
  };
  print("NIK:" + " " + karyawanPTXYZ['nik']);
  print("Nama Karyawan:" + " " + karyawanPTXYZ['nama']);
  print("Bagian:" + " " + karyawanPTXYZ['bagian']);

  // Object
  
  // Tipe 1
  
  Object dataLaptop1 = 'Laptop HP VICTUS';
  dataLaptop1 = 30000000;
  dataLaptop1 = true;

  print(dataLaptop1); //true
  
  // Tipe 2
  
  List<Object> dataLaptop2 = [
    'Laptop Lenovo LOQ',
    20000000,
    true
  ];

  print(dataLaptop2); //[Laptop Lenovo LOQ, 20000000, true] --> Karena berbentuk   list 
  
  //Dynamic
  
  dynamic nilaiFIKO = 80;
  nilaiFIKO = 90.5;
  nilaiFIKO = 'Sembilan puluh';
  print(nilaiFIKO; //Sembilan puluh --> karena dynamic mengambil nilai terakhir
  
//   dynamic nilaiBudi = 80;

//   nilaiBudi = 90.5;

//   print(nilaiBudi.toUpperCase());
  
  //Error karena angka / integer tidak bisa di uppercase
  
  /*Uncaught Error, error: Error: NoSuchMethodError: 'toUpperCase'
  Dynamic call failed.
  Tried to invoke `null` like a method.
  Receiver: 90.5
  Arguments: []*/
  
}
