# Input nilai tugas, UTS, UAS, dan kehadiran
nilai_tugas = float(input("Nilai tugas :"))
nilai_uts = float(input("Nilai UTS   :"))
nilai_uas = float(input("Nilai UAS   :"))
nilai_kehadiran = float(input("Kehadiran   :"))

# Rumus hitung nilai akhir 
nilai_akhir = (0.2 * nilai_tugas) + (0.3 * nilai_uts) + (0.5 * nilai_uas)

# lulus jika
if nilai_akhir >=85 and nilai_kehadiran >=90 and (nilai_akhir % 2 == 0):
    status = "LULUS DENGAN PREDIKAT"

elif nilai_akhir >=75 and nilai_kehadiran >= 80:
    status = "LULUS"

else:
    status = "BELUM LULUS"

#Output hasil
print ("nilai akhir :", nilai_akhir)
print ("status      :", status)

