# 🏴‍☠️ GitHub Profile README Setup Guide

Follow these steps to activate your Gear 5 × DFIR GitHub Profile README for **aslamxsthets**.

---

### 1. Create Your Special Profile Repository
1. Go to [github.com/new](https://github.com/new).
2. Set **Repository name** to: `aslamxsthets` (must match your GitHub username exactly).
3. Set the repository to **Public**.
4. Check **Add a README file** (or push an existing repository).

---

### 2. Add Your Files
Commit the following files into the `main` branch of `aslamxsthets/aslamxsthets`:
- `README.md` (The complete profile README)
- `assets/gear5-luffy.gif` (The authentic animated One Piece Luffy Gear 5 hero visual)
- `assets/gear5-banner.svg` (The Grand Line HUD banner embedding actual anime Luffy Gear 5)
- `assets/gear5-moon.gif` (The Gear 5 Drums of Liberation moon animation in Easter egg)
- `assets/cloud-divider.svg` (The Gear 5 cloud divider)
- `.github/workflows/snake.yml` (The contribution snake generator)

---

### 3. Enable Workflow Permissions for the Snake
1. In your `aslamxsthets/aslamxsthets` repository, navigate to **Settings** > **Actions** > **General**.
2. Scroll to **Workflow permissions**.
3. Select **Read and write permissions**.
4. Click **Save**.

---

### 4. Trigger & Verify the Contribution Snake
1. Go to the **Actions** tab in your repository.
2. Select **Generate Contribution Snake** from the left sidebar.
3. Click **Run workflow** > select `main` branch > click **Run workflow**.
4. Once the green checkmark appears, the workflow will automatically create and push the SVGs to the `output` branch.
5. Reload your GitHub profile at `https://github.com/aslamxsthets` to see your animated snake eating your contribution dots!

---

### 5. Customizing the Gear 5 Visual (Optional)
- The header is currently powered by `assets/gear5-banner.svg` (pure animated vector SVG, dark mode native, zero external dependencies).
- If you ever want to replace it with a custom GIF or high-resolution PNG:
  1. Place your file in `assets/` (e.g. `assets/gear5.gif`).
  2. In `README.md`, update line 5:
     ```html
     <img src="assets/gear5.gif" alt="Aslam Javeed — Gear 5 DFIR" width="100%" />
     ```
