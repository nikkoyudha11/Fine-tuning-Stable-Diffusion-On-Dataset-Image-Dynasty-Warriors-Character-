Dataset yang digunakan adalah dataset yang kami buat sendiri dengan menggunakan Huggingface dan berupa image dari character Dynasty Warriors. Bagian Fine-tuning dimulai pada code bagian 
!git clone https://huggingface.co/datasets/nikkoyudha/dynasty_warriors_characters 
Model Stable Diffusion yang kami gunakan adalah stabilityai/stable-diffusion-2-1 dengan 100 epoch. Kita bisa meningkatkan jumlah epochnya dengan menambahkan 
"max_training_epochs"
Sehingga hasil gambar yang dihasilkan lebih baik.
