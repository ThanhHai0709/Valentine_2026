let scale = 1;

function handleNo() {
    const yesBtn = document.querySelector('.btn-yes');

    // Tăng kích thước
    scale += 0.3;
    yesBtn.style.transform = `scale(${scale})`;

    // Random vị trí trên màn hình
    const maxX = window.innerWidth - yesBtn.offsetWidth;
    const maxY = window.innerHeight - yesBtn.offsetHeight;

    const randomX = Math.random() * maxX;
    const randomY = Math.random() * maxY;

    yesBtn.style.position = "fixed";
    yesBtn.style.left = randomX + "px";
    yesBtn.style.top = randomY + "px";
}

function handleYes() {
    // 1. Ẩn intro
    document.getElementById('screen-intro').classList.add('hidden');
    
    // 2. Hiện hoa
    const flowerWorld = document.getElementById('flower-world');
    document.body.classList.add('show-flower');
    flowerWorld.style.opacity = '1';

    // 3. Animation hoa chạy (sau 0.5s)
    setTimeout(() => {
        flowerWorld.classList.remove('paused');
    }, 500);

    // 4. Mưa tim
    startHeartRain();

    // 5. Hiện thư (sau 4s)
    setTimeout(() => {
        document.getElementById('myLetter').classList.add('show');
    }, 4000);

    // --- PHẦN MỚI THÊM: PHÁT NHẠC ---
    const audio = document.getElementById("bgMusic");
    
    // Chỉnh âm lượng (0.0 đến 1.0) - Đặt 50% cho đỡ chói tai
    audio.volume = 0.5; 
    
    // Lệnh phát nhạc
    audio.play().catch(function(error) {
        console.log("Trình duyệt chặn phát nhạc tự động: ", error);
        // Một số trình duyệt trên điện thoại có thể chặn nếu tương tác chưa đủ
    });
}

function closeLetter() {
    const letter = document.getElementById('myLetter');
    letter.style.opacity = '0';
    letter.style.transform = 'translate(-50%, -50%) scale(0.5)';
}

function startHeartRain() {
    setInterval(() => {
        const heart = document.createElement('div');
        heart.classList.add('heart');
        heart.innerHTML = '❤';
        heart.style.left = Math.random() * 100 + 'vw';
        const size = Math.random() * 20 + 10 + 'px';
        heart.style.fontSize = size;
        const duration = Math.random() * 3 + 3 + 's';
        heart.style.animationDuration = duration;
        document.body.appendChild(heart);
        
        setTimeout(() => { heart.remove(); }, 6000);
    }, 300);
}
