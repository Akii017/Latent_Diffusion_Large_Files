


# Latent Diffusion Large Files Repository

This repository contains large model checkpoints and weight files required for the main research project:  
👉 [Latent Diffusion Models Research](https://github.com/Akii017/latent_diffusion_research)

Due to GitHub LFS storage and bandwidth limitations, these files are hosted here separately.

---

## 📦 Repository Contents

```plaintext
Latent_Diffusion_Large_Files/
├── sd_checkpoints/
│   └── sd-v1-5/
│       ├── model.safetensors
│       ├── config.json
│       └── ...
├── controlnet/
│   ├── control_v11f1p_sd15_depth.pth
│   ├── control_v11p_sd15_canny.pth
│   └── ...
└── README.md


---

## 🔄 How to Use

### 1. Clone the Repository

```bash
git clone https://github.com/Akii017/Latent_Diffusion_Large_Files.git
```

### 2. Copy Model Files to Main Project

Replace `<path-to-main-repo>` with your actual project path:

```bash
cp -r Latent_Diffusion_Large_Files/sd_checkpoints <path-to-main-repo>/models/
cp -r Latent_Diffusion_Large_Files/controlnet <path-to-main-repo>/models/
```

### ✅ Expected Directory Structure

```plaintext
latent_diffusion_research/
└── models/
    ├── sd_checkpoints/
    └── controlnet/
```

Alternatively, you can use the script `scripts/download_models.py` provided in the main repo to automate model downloading and placement.

---

## 📌 Why a Separate Repo?

Due to GitHub LFS limitations, large binaries are kept in this dedicated repository to:

- ✅ Avoid LFS quota issues and overage errors
- 🚀 Improve cloning speed of the main repo
- 🧩 Maintain modularity and cleaner version control
- 🔄 Allow separate updates to large models without impacting core research code

---

## 📥 Related Repository

Check out the main project here:  
👉 **[latent_diffusion_research](https://github.com/Akii017/latent_diffusion_research)**

---

## 🛠 Maintainer

Developed and maintained by [Akii017](https://github.com/Akii017)

Feel free to open issues or pull requests if you have improvements or questions!
```

Let me know if you'd like a version with badges, GitHub actions support, or download links using `gdown` or Hugging Face!
