shift = int(raw_input("Enter Shift Number: ")) # menentukan jumlah pergesaran huruf
 
text = raw_input("Enter Text: ")
 
encryption = ""
 
for c in text:
 
    # mengecek apakah huruf kapital, kecil atau simbol
    if c.isupper()7:
 
        # menentukan nilai unicode(numerik) dari huruf kapital
        c_unicode = ord(c)
 
        c_index = ord(c) - ord("A")
 
        # melakukan pergeseran
        new_index = (c_index + shift) % 26
 
        # mengubah ke huruf yang baru
        new_unicode = new_index + ord("A")
 
        new_character = chr(new_unicode)
 
        # memasukkan huruf baru ke enkripsi
        encryption = encryption + new_character
 
    elif c.islower():
 
        # menentukan nilai unicode(numerik) dari huruf kecil
        c_unicode = ord(c)
 
        c_index = ord(c) - ord("a")
 
        # melakukan pergeseran
        new_index = (c_index + shift) % 26
 
        # mengubah ke huruf yang baru
        new_unicode = new_index + ord("a")
 
        new_character = chr(new_unicode)
 
        # memasukkan huruf baru ke enkripsi
        encryption = encryption + new_character
    else:
        # menentukan nilai unicode(numerik) dari
        c_index = ord(c)
        # melakukan pergeseran
        new_index = (c_index + shift)
 
        # mengubah ke huruf yang baru
        new_unicode = new_index
 
        new_character = chr(new_unicode)
 
        # memasukkan huruf baru ke enkripsi
        encryption = encryption + new_character  
 
print("Plain Text:",text)
 
print("Encrypted Text:",encryption)

