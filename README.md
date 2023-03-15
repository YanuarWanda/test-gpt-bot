## Line Account
* Line ID: @090tguod

## Referensi
* OpenAPI Completion Docs: https://platform.openai.com/docs/api-reference/completions/create

## Contoh
![Contoh Chat](https://lh3.googleusercontent.com/fife/AMPSemfmJosEdnPEfFIhCUGVN8jO7HFUprjcKEPbhTAsw0r__mLqgVcIggvRFnbF8vlH-zLLWqwgK1Y0UbR0NMc_FbzsUVXI1WsSwp9-esuPTQ0fHTi2fntjCCUUHH21jH3Ma9h2cqwop3lO5qOe-QLDFizPcnv9tM0MXa-u16EPTCEahgDcGiwhaJrN0Clf80JM43yZo9qcYnli0uBrNkh6M9LI3N3lMjVpD-Q8e-LDstM95oZKaNP2ji4ke6-AMQ7QKheSKWZUGzjTkoaQc99fWtoqE2Mdcbmcwd989ibhPyjuCpSEfz1eVpJOE3KjvKYQod3fA9a7KiArRSVx10jhR3t7yJpGVjatrbYh0Drcmb_JHceDpfmNN-4Ew2eil4hdRR93xzJQxnW8mGikpLCmBpZx7m4_5WMmP8KqMKwdHlCzFMNhMIDiYOJ8aJdC33fKHtILUcJtBMT4b9dBW1q9zMqbzmq83VzfWBZrSyOIfPgVGAzJ4dKKpxIgFkKGNFetqhuPMtIGhEoYkTJrigVyP3YU4cjZCOfcn_YUcclWyAtTrGBl7VaFGAiUzUScgbxb64TK-31TsiA_iSV4Clrr3lW-c80NnTU-8JR91oEAlCquc4ZWinHQ9ICF2vc3DcxSTJQ8Kd4hqO5UcurSY9BN2lAGKsB8B5RJY4QV6sGGAGCNU5EKtD3B27NYGI5t8JX2_9R2DD9seKXUhrDjUycbcrZa5Xp4EeSwa0zJKFTGFSqFiUtYC5VcYwPURb_2boVMTlUjb0gYw_LFTNTr2FQ78MC0r2BsrOzAcw9yfKavl6Lg2B8Imd8alpX90aHMfRaMPIITldSt6A7r7mnixgY9VuCUl6M2dpafVL_AGTVM_VbxSUwddIggBJJ8YolzJn7wTR3M43ZmpaVct0Dqz1tQ4f9MJkxxDPm2bHiFaWfzj2HaYBgMu0JOomW0Ym43ANax3lPm-90l9DynuMenxBAoEmC8523ROs2YE2SwW7B2c3aimLnL8LdPajfjK8Kub0CO7IFvFy3xDS9Yevqd3iSaDPNVpc6-JYOBqKd3eZgsWZcwf24ALEdNVSCHyQpOJ3mVGFLUFF8nJvSd4kfGn6sMhA=w1060-h1007)

## Catatan
1. Pake model dibawah ```text-davinci-003``` jawabannya jadi kurang nyambung. Tapi kalau pake ```text-davinci-003``` & misalkan jawabannya panjang, response dari API nya juga jadi lama.
2. API ```Chat```, di test dengan kasus yang sama responsenya lebih lama dibandingkan API ```Completions```.
3. Karena bot dari Kata ada batasan paling lama response API adalah 5 detik (Kalau lebih dari 5 detik akan return ```null```), jawaban kadang terpotong ditengah kalimat buat ngejaga biar response time nya engga lebih dari 5 detik.