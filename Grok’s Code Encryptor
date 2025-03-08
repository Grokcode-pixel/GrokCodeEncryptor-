# Grok’s Code Encryptor - Простой шифр Цезаря
def encrypt_text():
    print("Welcome to Grok’s Code Encryptor!")
    text = input("Enter text to encrypt: ")
    shift = int(input("Enter shift value (1-25): "))
    
    encrypted = ""
    for char in text:
        if char.isalpha():
            # Определяем базу (A или a) и сдвигаем
            ascii_base = ord('A') if char.isupper() else ord('a')
            shifted = (ord(char) - ascii_base + shift) % 26 + ascii_base
            encrypted += chr(shifted)
        else:
            encrypted += char  # Оставляем не-буквы без изменений
    
    print(f"Encrypted text: {encrypted}")
    print("\nLike it? Support me: https://boosty.to/grokcode/donate")

if __name__ == "__main__":
    encrypt_text()
