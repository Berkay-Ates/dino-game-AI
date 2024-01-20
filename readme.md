# Dino Game Deep Q-Network (DQN) Agent

Bu depo, Dino Oyunu'nu oynamak için eğitilmiş Bir Derin Q-Ağ (DQN) ajanı içeren kodu içerir. Ajan, Stable Baselines3 kütüphanesi kullanılarak uygulanmıştır.

## 1. Kurulum

Kodu çalıştırmadan önce gerekli bağımlılıkların yüklü olduğundan emin olun. Bunları yüklemek için aşağıdaki komutları kullanabilirsiniz:

```bash
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
pip install stable-baselines3[extra] protobuf==3.20.*
pip install mss 
pip install pydirectinput 
pip install pytesseract
pip install gym
