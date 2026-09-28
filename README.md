#Belajar Awal Dart
void main() {
  print("========================================");
  print("     KEGIATAN SEHARI-HARI ANDE SAPUTRA");
  print("========================================");

  String nama = "Ande Saputra";
  String nim = "1124160121";
  String kampus = "Global Institute";
  String jurusan = "Software Engineering";
  String kegiatan = "Bekerja di perusahaan ritel";
  int angkatan = 2024;
  double jamBelajar = 2.0;
  bool sudahKuliah = true;

  print("Nama          : $nama");
  print("NIM           : $nim");
  print("Kampus        : $kampus");
  print("Jurusan       : $jurusan");
  print("Angkatan      : $angkatan");
  print("Kegiatan      : $kegiatan");
  print("Waktu Belajar : Kurang lebih $jamBelajar jam per mata kuliah");
  print("Status Kuliah : $sudahKuliah");

  String? motivasi;
  motivasi = null;

  String pesanMotivasi = motivasi ?? "Mengembangkan skill dan ilmu pengetahuan";

  print("----------------------------------------");
  print("Motivasi      : $pesanMotivasi");
  print("---------------");
  print(
    "Tantangannya Saya masih sering kesusahan dalam belajar karena malas ataupun stop karena emang gak ngerti",
  );
  print(
    "Tetap semangat dan sehat selalu jangan menyerah demi hidup yang lebih baikk!",
  );
  print("========================================");
}
