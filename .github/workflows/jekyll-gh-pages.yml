<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Undangan Pernikahan: Joni & Verny</title>
    
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Montserrat:wght@300;400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

    <style>
        :root {
            --pink-romance: #f8bbd0;
            --blue-romance: #bbdefb;
            --dark-text: #4a4a4a;
        }

        body {
            font-family: 'Montserrat', sans-serif;
            color: var(--dark-text);
            overflow-x: hidden;
        }

        /* Parallax Sections */
        .parallax {
            height: 100vh;
            background-attachment: fixed;
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            position: relative;
        }

        .section-1 { background-image: url('https://images.unsplash.com/photo-1519741497674-611481863552?auto=format&fit=crop&q=80&w=1600'); }
        .section-2 { background-image: url('https://images.unsplash.com/photo-1511795409834-ef04bbd61622?auto=format&fit=crop&q=80&w=1600'); background-color: var(--blue-romance); }
        .section-3 { background-image: url('https://images.unsplash.com/photo-1465495910483-345749a2cc2b?auto=format&fit=crop&q=80&w=1600'); background-color: var(--pink-romance); }

        .overlay {
            position: absolute;
            top:0; left:0; right:0; bottom:0;
            background: rgba(255, 255, 255, 0.3);
        }

        /* Floating Menu */
        .floating-menu {
            position: fixed;
            bottom: 20px;
            left: 50%;
            transform: translateX(-50%);
            z-index: 1000;
            background: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(10px);
            padding: 10px 20px;
            border-radius: 50px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            display: flex;
            gap: 20px;
        }

        .floating-menu a {
            color: var(--dark-text);
            text-decoration: none;
            font-size: 1.2rem;
        }

        /* Hero Styling */
        .hero-text h1 {
            font-family: 'Great Vibes', cursive;
            font-size: 5rem;
            color: white;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        #timer {
            font-size: 1.5rem;
            font-weight: bold;
            background: rgba(255, 255, 255, 0.7);
            padding: 10px 20px;
            border-radius: 10px;
            margin-top: 20px;
        }

        /* Live Chat Styling */
        .chat-container {
            max-height: 300px;
            overflow-y: auto;
            background: #fff;
            padding: 15px;
            border-radius: 15px;
            box-shadow: inset 0 0 10px rgba(0,0,0,0.05);
        }
        .chat-bubble {
            background: var(--blue-romance);
            padding: 10px;
            border-radius: 15px;
            margin-bottom: 10px;
            animation: fadeIn 0.5s ease;
        }

        @keyframes fadeIn { from { opacity: 0; transform: translateY(10px); } to { opacity: 1; transform: translateY(0); } }

        .btn-pink { background-color: var(--pink-romance); border: none; }
        .btn-blue { background-color: var(--blue-romance); border: none; }
    </style>
</head>
<body>

    <nav class="floating-menu">
        <a href="#home" title="Home"><i class="fas fa-home"></i></a>
        <a href="#acara" title="Acara"><i class="fas fa-calendar-alt"></i></a>
        <a href="#hadiah" title="Hadiah"><i class="fas fa-gift"></i></a>
        <a href="#pesan" title="Ucapan"><i class="fas fa-comment"></i></a>
        <a href="#" data-bs-toggle="modal" data-bs-target="#qrModal" title="Scan QR"><i class="fas fa-qrcode"></i></a>
    </nav>

    <section id="home" class="parallax section-1">
        <div class="overlay"></div>
        <div class="container hero-text position-relative text-white">
            <div id="heroCarousel" class="carousel slide carousel-fade mb-4" data-bs-ride="carousel">
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <h1>Joni & Verny</h1>
                    </div>
                    <div class="carousel-item">
                        <h1>The Wedding</h1>
                    </div>
                </div>
            </div>
            <h3>Menuju Hari Bahagia</h3>
            <div id="timer" class="d-inline-block text-dark">00d 00h 00m 00s</div>
        </div>
    </section>

    <section id="acara" class="parallax section-2">
        <div class="container bg-white p-5 rounded-4 shadow position-relative">
            <h2 class="mb-4" style="font-family: 'Great Vibes'; font-size: 3rem;">Acara Pernikahan</h2>
            <p class="lead">Minggu, 19 April 2026</p>
            <p><strong>Pukul:</strong> 09.00 WIB - Selesai</p>
            <p><strong>Lokasi:</strong> Jalan Maju Mundur 12, Surabaya</p>
            <hr>
            <a href="https://www.google.com/maps?q=-7.2823682,112.6994013" target="_blank" class="btn btn-blue px-4 py-2 rounded-pill">
                <i class="fas fa-map-marker-alt"></i> Navigasi Lokasi
            </a>
        </div>
    </section>

    <section id="hadiah" class="parallax section-3">
        <div class="container">
            <div class="row g-4 justify-content-center">
                <div class="col-md-5">
                    <div class="card border-0 p-4 shadow-sm rounded-4">
                        <h4>Kirim Hadiah</h4>
                        <p>BCA - 12374892</p>
                        <p>a/n Joni Hamarlambang</p>
                        <button class="btn btn-pink text-white w-100 rounded-pill" onclick="copyToClipboard('12374892')">
                            <i class="fas fa-copy"></i> Copy No. Rekening
                        </button>
                    </div>
                </div>

                <div id="pesan" class="col-md-6">
                    <div class="card border-0 p-4 shadow-sm rounded-4">
                        <h4>Beri Ucapan & Doa</h4>
                        <div class="chat-container mb-3" id="chatBox">
                            <div class="chat-bubble"><strong>Budi:</strong> Selamat ya Joni & Verny! Samawa!</div>
                            <div class="chat-bubble"><strong>Siska:</strong> Lancar acaranya, see you there!</div>
                        </div>
                        <input type="text" id="guestName" class="form-control mb-2" placeholder="Nama Anda">
                        <textarea id="guestMessage" class="form-control mb-2" placeholder="Tulis ucapan..."></textarea>
                        <button class="btn btn-blue w-100 rounded-pill" id="sendBtn">Kirim Ucapan</button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <div class="modal fade" id="qrModal" tabindex="-1" aria-hidden="true">
        <div class="modal-dialog modal-dialog-centered">
            <div class="modal-content text-center p-4">
                <h3>QR Check-In</h3>
                <img src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=JoniVernyWeddingCheckIn" alt="QR Code" class="mx-auto my-3">
                <p>Gunakan kode ini untuk akses masuk tamu undangan.</p>
                <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Tutup</button>
            </div>
        </div>
    </div>

    <div class="toast-container position-fixed bottom-0 end-0 p-3">
        <div id="liveToast" class="toast" role="alert" aria-live="assertive" aria-atomic="true">
            <div class="toast-header bg-pink text-white">
                <strong class="me-auto">Sistem Undangan</strong>
                <button type="button" class="btn-close" data-bs-dismiss="toast" aria-label="Close"></button>
            </div>
            <div class="toast-body" id="toastMsg"></div>
        </div>
    </div>

    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

    <script>
        // 1. Countdown Timer
        const weddingDate = new Date("April 19, 2026 09:00:00").getTime();
        setInterval(function() {
            const now = new Date().getTime();
            const diff = weddingDate - now;
            const days = Math.floor(diff / (1000 * 60 * 60 * 24));
            const hours = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            const mins = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
            const secs = Math.floor((diff % (1000 * 60)) / 1000);
            $('#timer').html(`${days}d ${hours}h ${mins}m ${secs}s`);
        }, 1000);

        // 2. Copy to Clipboard
        function copyToClipboard(text) {
            navigator.clipboard.writeText(text);
            showToast("Nomor rekening berhasil dicopy!");
        }

        // 3. Live Chat / RSVP Logic
        $('#sendBtn').on('click', function() {
            const name = $('#guestName').val();
            const msg = $('#guestMessage').val();
            if(name && msg) {
                const newChat = `<div class="chat-bubble"><strong>${name}:</strong> ${msg}</div>`;
                $('#chatBox').append(newChat);
                $('#chatBox').scrollTop($('#chatBox')[0].scrollHeight);
                $('#guestName, #guestMessage').val('');
                showToast("Terima kasih atas ucapannya!");
            }
        });

        // 4. Toast Function
        function showToast(msg) {
            $('#toastMsg').text(msg);
            const toast = new bootstrap.Toast(document.getElementById('liveToast'));
            toast.show();
        }
    </script>
</body>
</html>
