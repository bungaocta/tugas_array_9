# tugas_array_9
#Inisialisasi array kamar
#'P' = Terisi, 'K' = Kosong
kamar = ['K', 'P', 'K', 'P', 'K', 'K', 'P', 'K', 'P', 'K']

# list nomor kamar kosong
kamar_kosong = []

#kamar yang kosong
for i in range(len(kamar)):
    if kamar[i] == 'K':
        kamar_kosong.append(i + 1)  # +1 karena index dimulai dari 0

print("Jumlah kamar kosong:", len(kamar_kosong))
print("Kamar yang kosong:", kamar_kosong)
