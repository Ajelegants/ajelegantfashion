<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>AJ Fashion | Ultra Premium Showcase</title>
<style>
    @import url('https://fonts.googleapis.com/css2?family=Cinzel:wght@400;700;900&family=Inter:wght@100;300;600&display=swap');

    body {
        margin: 0;
        padding: 0;
        background-color: #000;
        display: flex;
        justify-content: center;
        align-items: center;
        min-height: 100vh;
        overflow: hidden;
    }
    
    .preview-container {
        width: 1280px;
        height: 640px;
        background: #000;
        box-sizing: border-box;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        position: relative;
        overflow: hidden;
    }

    /* Subtle Animated Grain / Particles */
    .bg-texture {
        position: absolute;
        inset: 0;
        background-image: url("https://www.transparenttextures.com/patterns/carbon-fibre.png");
        opacity: 0.1;
        z-index: 1;
    }

    /* Luxury Spotlight Effect */
    .spotlight {
        position: absolute;
        width: 140%;
        height: 140%;
        background: radial-gradient(circle at 50% 50%, rgba(212, 175, 55, 0.12) 0%, transparent 60%);
        z-index: 2;
        animation: pulse 8s infinite alternate;
    }

    @keyframes pulse {
        0% { transform: scale(1); opacity: 0.8; }
        100% { transform: scale(1.1); opacity: 1; }
    }

    /* Glassmorphism Border Frame */
    .glass-frame {
        position: absolute;
        inset: 60px;
        border: 1px solid rgba(212, 175, 55, 0.3);
        background: rgba(255, 255, 255, 0.02);
        backdrop-filter: blur(5px);
        z-index: 3;
    }

    .content {
        z-index: 4;
        text-align: center;
    }

    .brand-top {
        font-family: 'Inter', sans-serif;
        color: #d4af37;
        text-transform: uppercase;
        letter-spacing: 20px;
        font-size: 14px;
        margin-bottom: 10px;
        font-weight: 300;
        opacity: 0.8;
    }

    h1 {
        font-family: 'Cinzel', serif;
        font-size: 160px;
        color: #fff;
        margin: 0;
        font-weight: 900;
        line-height: 0.9;
        background: linear-gradient(to bottom, #fff 40%, #d4af37 100%);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        letter-spacing: -5px;
    }

    .sub-title {
        font-family: 'Inter', sans-serif;
        font-size: 28px;
        color: rgba(255,255,255,0.6);
        margin-top: 20px;
        font-weight: 100;
        letter-spacing: 15px;
        text-transform: uppercase;
    }

    .divider {
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 20px;
        margin-top: 40px;
    }

    .line {
        width: 150px;
        height: 1px;
        background: linear-gradient(90deg, transparent, #d4af37, transparent);
    }

    .diamond {
        width: 8px;
        height: 8px;
        background: #d4af37;
        transform: rotate(45deg);
    }

    .footer-info {
        position: absolute;
        bottom: 100px;
        font-family: 'Inter', sans-serif;
        display: flex;
        gap: 60px;
        color: rgba(212, 175, 55, 0.5);
        font-size: 14px;
        letter-spacing: 4px;
        text-transform: uppercase;
        z-index: 4;
    }

    .signature {
        position: absolute;
        bottom: 30px;
        font-family: 'Cinzel', serif;
        color: rgba(255,255,255,0.1);
        font-size: 100px;
        white-space: nowrap;
        pointer-events: none;
        z-index: 1;
    }

    .username-footer {
        position: absolute;
        bottom: 30px;
        right: 80px;
        font-family: 'Inter', sans-serif;
        color: #d4af37;
        font-size: 12px;
        letter-spacing: 5px;
        text-transform: uppercase;
        z-index: 4;
        opacity: 0.7;
    }
</style>
</head>
<body>

    <div class="preview-container">
        <div class="bg-texture"></div>
        <div class="spotlight"></div>
        <div class="glass-frame"></div>
        
        <div class="signature">AUTHENTIC FASHION</div>

        <div class="content">
            <div class="brand-top">The Art of Dressing</div>
            <h1>AJ FASHION</h1>
            <div class="sub-title">Elite Lifestyle</div>
            
            <div class="divider">
                <div class="line"></div>
                <div class="diamond"></div>
                <div class="line"></div>
            </div>
        </div>
        
        <div class="footer-info">
            <span>• BESPOKE</span>
            <span>• LUXURY</span>
            <span>• ELEGANT</span>
        </div>

        <div class="username-footer">Designed by @aminparvez</div>
    </div>

</body>
</html>
