# ChatbotJKN
Final Project ini membahas pengembangan aplikasi chatbot informasi Program Jaminan Kesehatan Nasional (JKN) yang digunakan untuk memberikan informasi terkait regulasi dan ketentuan JKN berdasarkan peraturan perundang-undangan yang berlaku. Aplikasi chatbot dirancang agar pengguna dapat melakukan tanya jawab secara langsung mengenai informasi JKN melalui antarmuka berbasis web.

Pada pengembangan sistem ini, teknologi Artificial Intelligence (AI) yang digunakan adalah model Gemini versi gemini-3.1-flash-lite. Model ini digunakan untuk memproses pertanyaan pengguna dan menghasilkan jawaban yang relevan berdasarkan konteks informasi mengenai Program JKN. Penggunaan model Gemini dipilih karena memiliki performa yang ringan dan respons yang cepat untuk kebutuhan chatbot berbasis teks.

Sistem chatbot dikembangkan dengan konsep client-server, di mana aplikasi menerima input pertanyaan dari pengguna, kemudian meneruskannya ke API Gemini untuk diproses. Hasil respons dari AI selanjutnya ditampilkan kembali pada halaman aplikasi chatbot.

Untuk proses deployment dan pengujian aplikasi secara online, sistem menggunakan Ngrok sebagai tunneling service yang memungkinkan server lokal dapat diakses melalui internet. Dengan penggunaan Ngrok, proses testing dan demonstrasi aplikasi dapat dilakukan tanpa harus menggunakan hosting atau VPS secara langsung.

Melalui Final Project ini diharapkan aplikasi chatbot dapat menjadi implementasi sederhana pemanfaatan AI pada layanan informasi Program JKN dengan fokus pada integrasi AI, pemrosesan pertanyaan pengguna, dan deployment aplikasi berbasis web.
