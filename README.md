# Tutorial 8 - Game Development 2023/2024

> Godot Version: 3.5.3

## Latihan Mandiri: Rencana Polishing & Balancing Pada Game Proyek Kelompok

Refleksikan kegiatan playtesting terbuka yang diadakan di area kantin gedung baru Fasilkom UI.

1. Apa saja hal-hal positif yang kamu identifikasi dari pengalaman para pemain ketika mencoba game kelompok?

    Ada beberapa hal positif yang saya identifikasikan dari pengalaman para pemain ketika mencoba game kelompok sebagai berikut.

    - Mekanisme yang memungkinkan pemain menggunakan 3 karakter secara bergantian sering dilakukan oleh pemain untuk menyelesaikan level. Hal ini berarti mekanisme tersebut memiliki daya tarik tersendiri bagi pemain.
    - Kemampuan masing-masing karakter yang berbeda memiliki daya tarik bagi pemain. Pemain seringkali mengganti karakter untuk mencoba kemampuan yang dimiliki oleh masing-masing karakter untuk memperoleh keuntungan dalam melawan monster dan menyelesaikan level.
    - Ekplorasi level dengan pilihan bercabang meningkatkan rasa penasaran pemain dalam mengeksplorasi level yang ada. Hal ini sering dilakukan oleh pemain secara tidak sadar.
    - Jump scare pada beberapa ruang yang mengagetkan pemain yang membuat suasana permainan menjadi lebih seru dan asik.

1. Apa saja hal-hal negatif (atau, pain points) yang kamu identifikasi dari pengalaman para pemain ketika mencoba game kelompok?

    Ada beberapa hal negatif yang saya identifikasikan dari pengalaman para pemain ketika mencoba game kelompok sebagai berikut.

    - Bug. Pemain mengharapakan game yang bebas bug demi mengalami pengalaman permainan yang mengasikan dan tidak terlupakan. Namun, karena pada game yang kami buat masih terdapat bug, pemain kadang kala menemukan bug tersebut dan mengalami kebingungan.
    - Tutorial. Pemain membutuhkan tutorial untuk mengetahui aturan dan mekanik yang ada dalam permainan. Tutorial yang tidak ada atau kurang membantu dapat mengurangi pengalaman pemain dalam menyelesaikan level yang ada.
    - UI. UI yang minimal dapat menyebabkan kebingungan bagi pemain yang menyebabkan pengalaman bermain pemain menjadi terganggu.
    - Mekanik. Pemain mengharapkan perbedaan yang unik dari berbagai karakter, musuh, tempat, dan kemampuan yang ada dalam game.

2. Dari feedback-feedback yang telah diperoleh, apakah ada isu yang terkait pencapaian kondisi flow oleh pemain?
    - Misalnya, apakah ada tantangan di dalam game yang masih kurang tepat dengan kemampuan pemain pada level tertentu?

        Ya, ada beberapa pemain yang merasa bosan karena kemampuan pemain tersebut melebihi tantangan yang ada dalam permainan. Di sisi lain, ada pemain yang merasa kesulitan dalam menyelesaikan level yang ada.

    - Atau, apakah ada rancangan level di dalam game yang dirasa terlalu membosankan bagi pemain?

        Ya. Untuk pemain dengan kemampuan yang melebihi tantangan pada level awal dapat membuat pemain cukup bosan.

3. Dari jawaban kamu terhadap pertanyaan 1 hingga 3, tuliskan secara singkat, dalam bentuk bullet points, apa saja hal yang ingin kamu polish dan balance?

    - Mempolish mekanisme switch sehingga memberikan pemain pengalaman terbaik ketika mengganti karakter.
    - Menyesuaikan kemampuan masing-masing karakter dan menambahkan keunikan lebih lagi untuk masing-masing karakter.
    - Menyesuaikan dan memperbaiki level yang ada dengan peningkatan tantangan secara berkala demi memungkinkan pemain mengalami kondisi flow.
    - Memperbaiki seluruh bug yang ada hingga mencapai alpha dan gold build yang baik.
    - Menambahkan level tutorial untuk mengajarkan pemain terkait dengan aturan dan mekanik yang tersedia pada game sehingga pemain dapat memainkan game dengan lebih intuitif.
    - Menambahkan UI yang membantu pemain untuk mengetahu state dari permainan dan karakter yang sedang digunakan oleh pemain.

4. Untuk masing-masing poin di jawaban pertanyaan 4, jabarkan secara singkat (1 - 3 kalimat) mengenai rencana kerja kamu untuk mengimplementasikan usulan tersebut.
    - Mempolish mekanisme switch sehingga memberikan pemain pengalaman terbaik ketika mengganti karakter.

        **Rencana**: Menambahkan audio pergantian dan efek particle ketika pemain melakukan pergantian pemain sedemikian hingga pemain dapat merasakan pengalaman yang *pleasing*.

    - Menyesuaikan kemampuan masing-masing karakter dan menambahkan keunikan lebih lagi untuk masing-masing karakter.

        **Rencana**: menyesuaikan parameter yang dimiliki oleh setiap karakter (health, armor, dll.) dan kemampuan yang dimiliki oleh masing-masing karakter. Hal ini diperlukan untuk menciptakan karakter yang memiliki kekurangan dan kelebihan yang berbeda sehingga dapat dimanfatkan dalam strategi pemain untuk menyelesaikan level.

    - Menyesuaikan dan memperbaiki level yang ada dengan peningkatan tantangan secara berkala demi memungkinkan pemain mengalami kondisi flow.

        **Rencana**: Menambahkan variasi monster, kemampuan monster, jebakan, dll pada setiap level yang ada sedemikian hingga pemain menjadi lebih tertantang untuk menyelesaikan setiap level yang ada.

    - Memperbaiki seluruh bug yang ada hingga mencapai alpha dan gold build yang baik.

        **Rencana**: memperbaiki kode yang sudah ada dan bug yang telah ditemukan secara berkala hingga tidak ada bug pada permainan.

    - Menambahkan level tutorial untuk mengajarkan pemain terkait dengan aturan dan mekanik yang tersedia pada game sehingga pemain dapat memainkan game dengan lebih intuitif.

        **Rencana**: membuat level tutorial yang menjelaskan aturan dan mekanik dasar kepada pemain secara interaktif dan menyenangkan.

    - Menambahkan UI yang membantu pemain untuk mengetahu state dari permainan dan karakter yang sedang digunakan oleh pemain.

        **Rencana**: mendesain UI yang intuitif dan interaktif yang memungkinkan pengguna untuk mengetahui kondisi permainan dan karakter yang sedang digunakan.
