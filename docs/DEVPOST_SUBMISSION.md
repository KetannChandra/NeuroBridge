# Devpost Submission — Copy/Paste Pack

## Project Name
NeuroBridge — Early Risk & Care Connect

## Elevator Pitch
Capture daily neurological symptoms in 60 seconds, get a personalized early‑risk signal, and auto‑generate a doctor‑ready summary to bridge patients, families, and clinicians.

## About the Project
### Inspiration
Early neurological warning signs often go unnoticed, and communication between patients, families, and providers can be fragmented. We set out to make early signals **visible** and **shareable** with minimal friction.

### What it does
- **Capture**: Users log sleep, mood, headache, memory lapses, stress, and exercise in seconds.  
- **Detect**: A transparent 0–100 risk score highlights early signals and tracks trends.  
- **Connect**: Generates a concise 14‑day **doctor summary** + CSV export for clinical review.  
- **Personalize**: Provides adaptive tips and insights from each entry.

### How we built it
A fully client‑side web app using HTML, CSS, and vanilla JavaScript. Data is stored in the browser (`localStorage`). We implemented a lightweight canvas‑based chart (no external libraries) and an interpretable rule‑based risk model with trend analysis.

### What we learned
- UX details matter: users will actually log data if it’s fast and clear.  
- Simple, interpretable signals can still be clinically useful when combined with trend context.  
- Local‑first health tools reduce friction and improve privacy for rapid prototyping.

### Challenges
- Delivering a polished prototype under time pressure.  
- Balancing interpretability with usefulness (kept scoring simple and transparent).  
- Clarifying that this is not diagnostic while still being helpful.

### What’s next
- Optional secure cloud sync (with encryption).  
- Clinician view and HL7/FHIR export.  
- Optional AI layer (LLM) to summarize longer histories and surface patterns.  
- Accessibility audits with users.

### Safety & Ethics
Non-diagnostic; transparent rule weights; includes guidance to seek professional care for high‑risk results.

## Built With
- HTML, CSS, JavaScript (vanilla)
- Canvas (custom line chart)
- Browser localStorage
- (Docs) Matplotlib for the included sample PDF chart

## Try it out (Links)
- **Download the project** (open `index.html`): [NeuroBridge.zip](sandbox:/mnt/data/NeuroBridge.zip)
- **Sample doctor summary (PDF)**: [NeuroBridge_Sample_Doctor_Summary.pdf](sandbox:/mnt/data/NeuroBridge/summary/NeuroBridge_Sample_Doctor_Summary.pdf)
- **Sample data (CSV)**: [sample_logs.csv](sandbox:/mnt/data/NeuroBridge/data/sample_logs.csv)

## Repository
You can upload the provided ZIP to GitHub as-is.

## Media
Use the included 3:2 images:
- `assets/cover1.png`
- `assets/cover2.png`

## Acknowledgements
Built for NeuraVia Hacks — prompt: *Capturing medical data for interactive software*.
