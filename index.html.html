<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>청춘합창단 이벤트</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Pretendard', -apple-system, BlinkMacSystemFont, "Segoe UI", "Malgun Gothic", sans-serif;
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            position: relative;
            overflow: hidden;
        }

        body::before {
            content: '';
            position: absolute;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255,255,255,0.1) 1px, transparent 1px);
            background-size: 50px 50px;
            animation: backgroundMove 20s linear infinite;
        }

        @keyframes backgroundMove {
            0% { transform: translate(0, 0); }
            100% { transform: translate(50px, 50px); }
        }

        .container {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            border-radius: 30px;
            padding: 50px 40px;
            max-width: 500px;
            width: 100%;
            box-shadow: 0 30px 80px rgba(0, 0, 0, 0.3);
            text-align: center;
            position: relative;
            z-index: 1;
            animation: slideUp 0.6s ease-out;
        }

        @keyframes slideUp {
            from {
                opacity: 0;
                transform: translateY(50px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .result-icon {
            font-size: 120px;
            margin-bottom: 20px;
            animation: bounceIn 0.8s cubic-bezier(0.68, -0.55, 0.265, 1.55);
            text-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
        }

        @keyframes bounceIn {
            0% {
                transform: scale(0) rotate(-180deg);
                opacity: 0;
            }
            60% {
                transform: scale(1.2) rotate(10deg);
            }
            100% {
                transform: scale(1) rotate(0deg);
                opacity: 1;
            }
        }

        .result-title {
            font-size: 48px;
            font-weight: 800;
            color: #333;
            letter-spacing: -1px;
        }

        .winner-gold {
            background: linear-gradient(135deg, #FFD700 0%, #FFA500 100%);
            color: white;
            padding: 40px;
            border-radius: 25px;
            margin-bottom: 30px;
            box-shadow: 
                0 15px 35px rgba(255, 215, 0, 0.4),
                inset 0 -5px 15px rgba(0, 0, 0, 0.1);
            position: relative;
            overflow: hidden;
        }

        .winner-gold::before {
            content: '✨';
            position: absolute;
            font-size: 60px;
            opacity: 0.2;
            top: -10px;
            right: -10px;
            animation: sparkle 2s infinite;
        }

        @keyframes sparkle {
            0%, 100% { transform: rotate(0deg) scale(1); opacity: 0.2; }
            50% { transform: rotate(180deg) scale(1.2); opacity: 0.4; }
        }

        .winner-silver {
            background: linear-gradient(135deg, #E8E8E8 0%, #B0B0B0 100%);
            color: #333;
            padding: 40px;
            border-radius: 25px;
            margin-bottom: 30px;
            box-shadow: 
                0 15px 35px rgba(192, 192, 192, 0.4),
                inset 0 -5px 15px rgba(0, 0, 0, 0.1);
            position: relative;
            overflow: hidden;
        }

        .winner-silver::before {
            content: '⭐';
            position: absolute;
            font-size: 60px;
            opacity: 0.2;
            top: -10px;
            right: -10px;
            animation: sparkle 2s infinite;
        }

        .winner-bronze {
            background: linear-gradient(135deg, #E89F71 0%, #A67C52 100%);
            color: white;
            padding: 40px;
            border-radius: 25px;
            margin-bottom: 30px;
            box-shadow: 
                0 15px 35px rgba(205, 127, 50, 0.4),
                inset 0 -5px 15px rgba(0, 0, 0, 0.1);
            position: relative;
            overflow: hidden;
        }

        .winner-bronze::before {
            content: '🌟';
            position: absolute;
            font-size: 60px;
            opacity: 0.2;
            top: -10px;
            right: -10px;
            animation: sparkle 2s infinite;
        }

        @keyframes confetti-fall {
            to {
                transform: translateY(100vh) rotate(360deg);
                opacity: 0;
            }
        }

        /* 모바일 최적화 */
        @media (max-width: 480px) {
            .container {
                padding: 40px 30px;
            }
            
            .result-icon {
                font-size: 100px;
            }
            
            .result-title {
                font-size: 32px;
            }
            
            .result-message {
                font-size: 16px;
            }
        }
    </style>
</head>
<body>
    <div class="container" id="resultContainer">
        <!-- 결과가 여기에 동적으로 표시됩니다 -->
    </div>

    <script>
        // 설정 - 당첨 확률 (100% 당첨, 등수만 다름)
        const PRIZES = {
            first: 0.20,    // 1등: 20%
            second: 0.30,   // 2등: 30%
            third: 0.50     // 3등: 50%
        };

        // 당첨 등수 결정
        function determineResult() {
            const random = Math.random();
            
            if (random < PRIZES.first) {
                return { 
                    prize: 'first', 
                    icon: '🏆', 
                    title: '1등 당첨!', 
                    color: 'winner-gold' 
                };
            } else if (random < PRIZES.first + PRIZES.second) {
                return { 
                    prize: 'second', 
                    icon: '🥈', 
                    title: '2등 당첨!', 
                    color: 'winner-silver' 
                };
            } else {
                return { 
                    prize: 'third', 
                    icon: '🥉', 
                    title: '3등 당첨!', 
                    color: 'winner-bronze' 
                };
            }
        }

        const result = determineResult();

        // 페이지 로드 시 결과 표시
        window.addEventListener('DOMContentLoaded', () => {
            displayResult(result);
            createConfetti();
        });

        function displayResult(result) {
            const container = document.getElementById('resultContainer');
            
            container.innerHTML = `
                <div class="result-icon">${result.icon}</div>
                <div class="${result.color}">
                    <div class="result-title">${result.title}</div>
                </div>
            `;
        }

        function createConfetti() {
            const colors = ['#ff6b6b', '#4ecdc4', '#45b7d1', '#f9ca24', '#6c5ce7'];
            const confettiCount = 50;
            
            for (let i = 0; i < confettiCount; i++) {
                setTimeout(() => {
                    const confetti = document.createElement('div');
                    confetti.style.position = 'fixed';
                    confetti.style.width = '10px';
                    confetti.style.height = '10px';
                    confetti.style.backgroundColor = colors[Math.floor(Math.random() * colors.length)];
                    confetti.style.left = Math.random() * 100 + '%';
                    confetti.style.top = '-10px';
                    confetti.style.opacity = '1';
                    confetti.style.transform = 'rotate(' + (Math.random() * 360) + 'deg)';
                    confetti.style.animation = `confetti-fall ${2 + Math.random() * 2}s linear`;
                    
                    document.body.appendChild(confetti);
                    
                    setTimeout(() => {
                        confetti.remove();
                    }, 4000);
                }, i * 30);
            }
        }
    </script>
</body>
</html>
