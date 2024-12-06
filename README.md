# Araç Kiralama Sistemi

Bu C++ programı, araç kiralama işlemlerini yönetmek için kullanılır. Kullanıcılar araç kiralayabilir, araç iade edebilir ve bakiye durumlarını kontrol edebilirler.

## Özellikler

- Araç kiralama işlemi başlatma
- Araç iade işlemi yapma
- Kiralama ücretini hesaplama ve bakiyeden düşme
- Yetersiz bakiye durumunda uyarı verme

## Gereksinimler

- C++ derleyicisi (örneğin, g++)

## Kurulum

1. Depoyu klonlayın:
    ```sh
    git clone https://github.com/abdullah-aksoy/arac-kiralama
    cd arac-kiralama
    ```

2. Programı derleyin:
    ```sh
    g++ -o arac_kiralama arac-kiralama.cpp
    ```

## Kullanım

1. Derlenmiş programı çalıştırın:
    ```sh
    ./arac-kiralama
    ```

2. Menüden bir işlem seçin ve istenen değerleri girin.

## Kod Açıklaması

Program aşağıdaki adımları gerçekleştirir:

1. Kullanıcıdan bakiye bilgisi alır.
2. Kullanıcıdan işlem seçimi yapmasını ister.
3. Seçilen işleme göre gerekli değerleri kullanıcıdan alır.
4. Hesaplamaları yapar ve sonuçları ekrana yazdırır.
5. Kullanıcı çıkış yapana kadar bu işlemleri tekrarlar.
