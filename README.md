import tkinter as tk

def menu():
    root = tk.Tk()
    root.geometry("300x200")
    root.title("Menü")

    label = tk.Label(root, text="Hoş Geldiniz!", font=("Arial", 16))
    label.pack(pady=20)

    button1 = tk.Button(root, text="Sisteme Üye Ol")
    button1.pack(pady=10)

    button2 = tk.Button(root, text="Sisteme Giriş Yap")
    button2.pack(pady=10)

    button3 = tk.Button(root, text="Şifremi Unuttum")
    button3.pack(pady=10)

    root.mainloop()

menu()
