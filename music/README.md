# Музыка для слайд-шоу

10 треков, сгенерированных алгоритмически (синтез в Python: numpy + scipy, кодирование LAME).
Никаких сторонних сэмплов и чужих прав — **CC0 / public domain**, можно использовать свободно.

| Файл | Название | Жанр | BPM | Длина |
|---|---|---|---|---|
| track01.mp3 | Vice House | house | 124 | 0:41 |
| track02.mp3 | Neon Drive | synthwave | 100 | 0:45 |
| track03.mp3 | Phonk Alley | phonk | 140 | 0:40 |
| track04.mp3 | Leonida Lofi | lo-fi | 78 | 0:45 |
| track05.mp3 | Trap Dollar | trap | 140 | 0:40 |
| track06.mp3 | Vice DnB | drum & bass | 174 | 0:27 |
| track07.mp3 | Ocean Drive | tropical | 105 | 0:43 |
| track08.mp3 | Electro Neon | electro | 128 | 0:40 |
| track09.mp3 | Drill Season | drill | 142 | 0:36 |
| track10.mp3 | Leonida Sunrise | cinematic | 90 | 0:34 |

Всего ≈ 5,2 МБ, 112 кбит/с, 44,1 кГц, стерео.

Плеер в `index.html` играет эти файлы с того же домена, поэтому анализатор спектра
работает на настоящем FFT (Web Audio AnalyserNode), а не на модели темпа.
