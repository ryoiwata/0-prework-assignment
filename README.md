# Prework Assignment

## Step 1: Fork This Repository

**You must fork this repository to your own GitHub account before starting.**

1. Click the **Fork** button at the top right of this page
2. Clone your forked repository to your local machine:

```bash
git clone https://github.com/YOUR_USERNAME/0-prework-assignment.git
cd 0-prework-assignment
```

## Step 2: Run the Jupyter Notebook

Start the notebook server:

```bash
docker compose up --build
```

Open your browser to **http://localhost:8888**

## Step 3: Complete the Assignment

Open `Check_for_Understanding.ipynb` and add your answers to all exercises.

When finished, save your notebook (Ctrl+S or File → Save).

Stop the server with `Ctrl+C`, then:

```bash
docker compose down
```

## Step 4: Push Your Answers

Commit and push your completed notebook to your forked repository:

```bash
git add .
git commit -m "Completed prework assignment"
git push origin main
```

## Step 5: Submit on the Gauntlet Portal

1. Go to **[portal.gauntletai.com](https://portal.gauntletai.com)**
2. Submit the link to your forked repository
