# YouTube Analytics Dashboard

A Streamlit-powered dashboard analyzing top YouTube channels, their performance metrics, and trends. This project implements various data visualizations and machine learning models to derive insights from YouTube channel data.

## Features

- Top 100 YouTube channel category distribution
- Predictive analysis of likes vs. subscribers relationship
- Global YouTuber distribution
- Annual view trends for top channels
- Revenue analysis
- Channel clustering based on performance metrics
- Category-wise follower analysis
- Top performing channels visualization

## Technologies Used

- Python 3.x
- Streamlit
- Pandas & NumPy
- Scikit-learn
- Plotly
- Seaborn
- Matplotlib

## Installation

```bash
git clone https://github.com/cam-cc/youtube-analytics.git
cd youtube-analytics
pip install -r requirements.txt
```

## Usage

Run the Streamlit app:
```bash
streamlit run app.py
```

## Project Structure

```
├── app.py              # Main Streamlit application
├── data/              # Data files
├── src/               # Source code
│   ├── preprocessing/ # Data preprocessing scripts
│   ├── models/        # ML models
│   └── visualization/ # Visualization functions
└── requirements.txt   # Project dependencies
```

## License

MIT

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request