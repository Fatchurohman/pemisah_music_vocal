* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: linear-gradient(135deg, #1a1a2e 0%, #16213e 50%, #0f3460 100%);
    min-height: 100vh;
    position: relative;
    overflow-x: hidden;
}

.background-overlay {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: radial-gradient(circle at 20% 50%, rgba(212, 175, 55, 0.1) 0%, transparent 50%),
                radial-gradient(circle at 80% 80%, rgba(255, 215, 0, 0.1) 0%, transparent 50%);
    pointer-events: none;
    z-index: 0;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
    position: relative;
    z-index: 1;
}

/* Header Styles */
.header {
    text-align: center;
    margin-bottom: 50px;
    padding-top: 30px;
}

.main-title {
    font-size: 3.5rem;
    font-weight: 800;
    background: linear-gradient(135deg, #ffd700 0%, #ffed4e 50%, #d4af37 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    text-shadow: 0 0 30px rgba(255, 215, 0, 0.3);
    margin-bottom: 20px;
    animation: titleGlow 3s ease-in-out infinite;
}

@keyframes titleGlow {
    0%, 100% {
        filter: brightness(1);
    }
    50% {
        filter: brightness(1.2);
    }
}

.developer-info {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 12px;
}

.blink-dot {
    width: 12px;
    height: 12px;
    background: linear-gradient(135deg, #ffd700, #ffed4e);
    border-radius: 50%;
    animation: blink 1.5s ease-in-out infinite;
    box-shadow: 0 0 20px rgba(255, 215, 0, 0.8);
}

@keyframes blink {
    0%, 100% {
        opacity: 1;
        transform: scale(1);
    }
    50% {
        opacity: 0.3;
        transform: scale(0.8);
    }
}

.developer-text {
    color: #ffd700;
    font-size: 1.1rem;
    font-weight: 600;
    letter-spacing: 1px;
}

/* Upload Section */
.upload-section {
    margin-bottom: 40px;
}

.upload-card {
    background: linear-gradient(135deg, rgba(255, 215, 0, 0.1) 0%, rgba(212, 175, 55, 0.05) 100%);
    border: 2px solid rgba(255, 215, 0, 0.3);
    border-radius: 30px;
    padding: 50px;
    backdrop-filter: blur(10px);
    box-shadow: 0 20px 60px rgba(255, 215, 0, 0.2),
                inset 0 1px 0 rgba(255, 255, 255, 0.1);
    text-align: center;
}

.upload-icon {
    font-size: 4rem;
    margin-bottom: 20px;
    animation: float 3s ease-in-out infinite;
}

@keyframes float {
    0%, 100% {
        transform: translateY(0);
    }
    50% {
        transform: translateY(-10px);
    }
}

.upload-card h2 {
    color: #ffd700;
    font-size: 2rem;
    margin-bottom: 10px;
}

.subtitle {
    color: rgba(255, 215, 0, 0.7);
    font-size: 1.1rem;
    margin-bottom: 30px;
}

.upload-area {
    margin: 30px 0;
}

.upload-label {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 60px;
    border: 3px dashed rgba(255, 215, 0, 0.5);
    border-radius: 20px;
    background: rgba(255, 215, 0, 0.05);
    cursor: pointer;
    transition: all 0.3s ease;
    color: #ffd700;
}

.upload-label:hover {
    border-color: #ffd700;
    background: rgba(255, 215, 0, 0.1);
    transform: translateY(-5px);
    box-shadow: 0 10px 30px rgba(255, 215, 0, 0.3);
}

.upload-label svg {
    margin-bottom: 20px;
}

.upload-text {
    font-size: 1.3rem;
    font-weight: 600;
    margin-bottom: 10px;
}

.file-info {
    font-size: 0.9rem;
    color: rgba(255, 215, 0, 0.6);
}

/* File Selected */
.file-selected {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 25px;
    background: rgba(255, 215, 0, 0.1);
    border: 2px solid rgba(255, 215, 0, 0.3);
    border-radius: 15px;
    margin: 20px 0;
}

.file-icon {
    font-size: 2.5rem;
}

.file-details {
    flex: 1;
    margin: 0 20px;
    text-align: left;
}

.file-name {
    display: block;
    color: #ffd700;
    font-weight: 600;
    font-size: 1.1rem;
    margin-bottom: 5px;
}

.file-size {
    display: block;
    color: rgba(255, 215, 0, 0.6);
    font-size: 0.9rem;
}

.remove-btn {
    background: rgba(255, 0, 0, 0.2);
    border: 2px solid rgba(255, 0, 0, 0.5);
    color: #ff6b6b;
    width: 40px;
    height: 40px;
    border-radius: 50%;
    cursor: pointer;
    font-size: 1.2rem;
    transition: all 0.3s ease;
}

.remove-btn:hover {
    background: rgba(255, 0, 0, 0.3);
    transform: rotate(90deg);
}

/* Process Button */
.process-btn {
    background: linear-gradient(135deg, #ffd700 0%, #d4af37 100%);
    border: none;
    color: #1a1a2e;
    padding: 18px 50px;
    font-size: 1.2rem;
    font-weight: 700;
    border-radius: 50px;
    cursor: pointer;
    display: inline-flex;
    align-items: center;
    gap: 15px;
    transition: all 0.3s ease;
    box-shadow: 0 10px 30px rgba(255, 215, 0, 0.4);
    margin-top: 20px;
}

.process-btn:hover:not(:disabled) {
    transform: translateY(-3px);
    box-shadow: 0 15px 40px rgba(255, 215, 0, 0.6);
}

.process-btn:disabled {
    opacity: 0.5;
    cursor: not-allowed;
}

/* Processing Section */
.processing-card {
    background: linear-gradient(135deg, rgba(255, 215, 0, 0.1) 0%, rgba(212, 175, 55, 0.05) 100%);
    border: 2px solid rgba(255, 215, 0, 0.3);
    border-radius: 30px;
    padding: 60px;
    text-align: center;
    backdrop-filter: blur(10px);
}

.spinner {
    width: 80px;
    height: 80px;
    border: 6px solid rgba(255, 215, 0, 0.2);
    border-top-color: #ffd700;
    border-radius: 50%;
    animation: spin 1s linear infinite;
    margin: 0 auto 30px;
}

@keyframes spin {
    to {
        transform: rotate(360deg);
    }
}

.processing-card h3 {
    color: #ffd700;
    font-size: 2rem;
    margin-bottom: 15px;
}

.processing-card p {
    color: rgba(255, 215, 0, 0.7);
    font-size: 1.1rem;
    margin-bottom: 30px;
}

.progress-bar {
    width: 100%;
    height: 12px;
    background: rgba(255, 215, 0, 0.2);
    border-radius: 10px;
    overflow: hidden;
    margin-bottom: 15px;
}

.progress-fill {
    height: 100%;
    background: linear-gradient(90deg, #ffd700, #ffed4e);
    border-radius: 10px;
    width: 0%;
    transition: width 0.3s ease;
    box-shadow: 0 0 20px rgba(255, 215, 0, 0.6);
}

.progress-text {
    color: #ffd700;
    font-weight: 600;
    font-size: 1.1rem;
}

/* Download Section */
.download-card {
    background: linear-gradient(135deg, rgba(255, 215, 0, 0.1) 0%, rgba(212, 175, 55, 0.05) 100%);
    border: 2px solid rgba(255, 215, 0, 0.3);
    border-radius: 30px;
    padding: 50px;
    backdrop-filter: blur(10px);
    text-align: center;
}

.success-icon {
    width: 100px;
    height: 100px;
    background: linear-gradient(135deg, #ffd700, #ffed4e);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 3rem;
    color: #1a1a2e;
    margin: 0 auto 30px;
    animation: successPulse 2s ease-in-out infinite;
    box-shadow: 0 0 40px rgba(255, 215, 0, 0.6);
}

@keyframes successPulse {
    0%, 100% {
        transform: scale(1);
    }
    50% {
        transform: scale(1.1);
    }
}

.download-card h2 {
    color: #ffd700;
    font-size: 2.5rem;
    margin-bottom: 15px;
}

.success-text {
    color: rgba(255, 215, 0, 0.7);
    font-size: 1.2rem;
    margin-bottom: 40px;
}

.download-options {
    display: grid;
    gap: 20px;
    margin-bottom: 30px;
}

.download-item {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 25px;
    background: rgba(255, 215, 0, 0.05);
    border: 2px solid rgba(255, 215, 0, 0.2);
    border-radius: 20px;
    transition: all 0.3s ease;
}

.download-item:hover {
    background: rgba(255, 215, 0, 0.1);
    border-color: rgba(255, 215, 0, 0.4);
    transform: translateX(10px);
}

.download-item.featured {
    border: 2px solid rgba(255, 215, 0, 0.5);
    background: rgba(255, 215, 0, 0.15);
}

.download-icon {
    font-size: 2.5rem;
    margin-right: 20px;
}

.download-info {
    flex: 1;
    text-align: left;
}

.download-info h4 {
    color: #ffd700;
    font-size: 1.3rem;
    margin-bottom: 5px;
}

.download-info p {
    color: rgba(255, 215, 0, 0.6);
    font-size: 0.95rem;
}

.download-btn {
    background: linear-gradient(135deg, #ffd700, #d4af37);
    border: none;
    color: #1a1a2e;
    padding: 12px 30px;
    border-radius: 30px;
    font-weight: 600;
    cursor: pointer;
    display: flex;
    align-items: center;
    gap: 10px;
    transition: all 0.3s ease;
    box-shadow: 0 5px 20px rgba(255, 215, 0, 0.3);
}

.download-btn:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 25px rgba(255, 215, 0, 0.5);
}

.reset-btn {
    background: transparent;
    border: 2px solid #ffd700;
    color: #ffd700;
    padding: 15px 40px;
    font-size: 1.1rem;
    font-weight: 600;
    border-radius: 30px;
    cursor: pointer;
    transition: all 0.3s ease;
}

.reset-btn:hover {
    background: rgba(255, 215, 0, 0.1);
    transform: translateY(-2px);
}

/* Particles */
.particles {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    pointer-events: none;
    z-index: 0;
}

.particle {
    position: absolute;
    width: 4px;
    height: 4px;
    background: #ffd700;
    border-radius: 50%;
    animation: particleFloat 15s infinite;
    opacity: 0.6;
}

.particle:nth-child(1) {
    left: 10%;
    animation-delay: 0s;
}

.particle:nth-child(2) {
    left: 30%;
    animation-delay: 3s;
}

.particle:nth-child(3) {
    left: 50%;
    animation-delay: 6s;
}

.particle:nth-child(4) {
    left: 70%;
    animation-delay: 9s;
}

.particle:nth-child(5) {
    left: 90%;
    animation-delay: 12s;
}

@keyframes particleFloat {
    0% {
        transform: translateY(100vh) scale(0);
        opacity: 0;
    }
    10% {
        opacity: 0.6;
    }
    90% {
        opacity: 0.6;
    }
    100% {
        transform: translateY(-100px) scale(1);
        opacity: 0;
    }
}

/* Responsive */
@media (max-width: 768px) {
    .main-title {
        font-size: 2rem;
    }
    
    .upload-card,
    .processing-card,
    .download-card {
        padding: 30px 20px;
    }
    
    .upload-label {
        padding: 40px 20px;
    }
    
    .download-item {
        flex-direction: column;
        text-align: center;
        gap: 15px;
    }
    
    .download-info {
        text-align: center;
    }
}
