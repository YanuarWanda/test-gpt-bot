## Line Account
* Line ID: @090tguod
* QR Code<br/>
![QR Code Line](https://i.imgur.com/Y0ZJQN3.png)

## Referensi
* OpenAPI Completion Docs: https://platform.openai.com/docs/api-reference/completions/create

## Contoh
![Contoh Chat](https://i.imgur.com/Ez1eQNX.jpeg)

## Catatan
1. Pake model dibawah ```text-davinci-003``` jawabannya jadi kurang nyambung. Tapi kalau pake ```text-davinci-003``` & misalkan jawabannya panjang, response dari API nya juga jadi lama.
2. API ```Chat```, di test dengan kasus yang sama responsenya lebih lama dibandingkan API ```Completions```.
3. Karena bot dari Kata ada batasan paling lama response API adalah 5 detik (Kalau lebih dari 5 detik akan return ```null```), jawaban kadang terpotong ditengah kalimat buat ngejaga biar response time nya engga lebih dari 5 detik.