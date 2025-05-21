class mahasiswa:
    def __init__(self, nim=0,nama="siapa",IPK="angka"):
        self.nim = nim
        self.nama = nama
        self.IPK = IPK
    
    def tampilkan_info(self):
        print(f"biodata = {self.nama} dengan nim {self.nim} dari {self.IPK}")

mahasiswa1 = mahasiswa ("andre", "452024611003", "4.0")
mahasiswa2 = mahasiswa ("andre", "452024611003")
mahasiswa3 = mahasiswa ("andre")
mahasiswa4 = mahasiswa ()

mahasiswa1.tampilkan_info()
mahasiswa2.tampilkan_info()
mahasiswa3.tampilkan_info()
mahasiswa4.tampilkan_info()

