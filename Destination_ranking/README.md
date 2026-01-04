# Weekend Getaway Ranker

A Python recommendation engine that suggests **top weekend travel destinations** in India based on **distance, rating, and popularity** from a given source city.

This project uses a dataset of popular Indian cities and calculates approximate distances between cities to rank destinations.

---

## Features

- Input a **source city** and get the **top 5 nearby destinations**.
- Ranks destinations based on:
  - **Distance** (closer is better)
  - **Rating** (higher is better)
  - **Popularity** (higher is better)
- Easy-to-use Python script using **Pandas**.
- Outputs a **table with city, state, distance, rating, popularity, and score**.

---

## Dataset

- `travel_dataset.csv` contains sample city data:
  - `City`, `State`, `Latitude`, `Longitude`, `Rating`, `Popularity`
- You can expand it or replace it with a larger dataset from Kaggle or other sources.

---

## Installation

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/weekend-getaway-ranker.git
cd weekend-getaway-ranker
