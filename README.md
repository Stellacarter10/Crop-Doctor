# Crop Doctor

Crop Doctor is a lightweight, zero-dependency web app designed to help smallholder farmers identify common crop problems and get simple, low-cost guidance for treatment.

It works offline on basic smartphones and does not require any installation, database, or external service.

## What the app does

- Lets you choose the crop you are growing
- Shows common symptom groups such as yellow leaves, holes/bites, spots, wilting, or stunted growth
- Gives likely causes based on the crop and symptom
- Suggests practical actions farmers can try immediately
- Recommends checking more than one plant before treating

## How to use the app

### 1. Open the app

You can use it in either of these ways:

- Open `index.html` directly in your browser
- Or run a simple local web server and open it in the browser

Example:

```bash
cd Crop-Doctor
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

### 2. Select your crop

From the dropdown menu, choose the crop you are growing, such as:

- Maize
- Cassava
- Tomato
- Beans
- Cowpea
- Groundnut

### 3. Tap the main symptom

Choose the symptom that best matches what you see in the field, for example:

- Yellow leaves
- Holes / bites
- Spots / lesions
- Wilting / drooping
- Poor growth / stunted plants

### 4. Read the advice

The app will show:

- possible causes
- what to check in the field
- basic low-cost management steps
- safety reminders relevant to the crop and symptom

### 5. Use the guidance with field checks

The app is meant to support decision-making, not replace a local agronomist or plant doctor. It is best to:

- inspect several plants before deciding
- check crop health across the field
- look at soil moisture, drainage, pest damage, and leaf patterns
- ask a local farm adviser if damage spreads quickly or becomes severe

## Offline use

This app is designed to work without internet access. Because it has no dependencies, it can run from a phone or computer even when you are in the field.

## Quick example

1. Open the app
2. Select `Maize`
3. Tap `🐛 Holes / bites`
4. Read the advice about possible pests, scouting tips, and low-cost action steps

## Notes

- This is a decision-support tool for general guidance
- It does not provide a guaranteed diagnosis
- Always verify the issue with local field observation and expert advice when needed

## Project files

- `index.html` — main app interface and logic
- `README.md` — usage guide

## License

This project is distributed without a formal license file. If you plan to reuse or share it, confirm with the repository owner before using it in commercial or public projects.
