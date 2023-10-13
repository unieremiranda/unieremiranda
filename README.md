import hashlib

myText = 'Em 1999 iniciam-se as atividades da FCI (Faculdade de Informática), como o curso de Ciência da Computação.'

SHA256 = hashlib.sha256(myText.encode('utf-8')).hexdigest()
MD5 = hashlib.md5(myText.encode('utf-8')).hexdigest()

print("\"" +myText + "\" - " + SHA256 + " - " + MD5)


