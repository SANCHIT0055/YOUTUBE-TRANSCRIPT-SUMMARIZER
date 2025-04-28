
# YouTube Transcript Summarizer  

A Flask-based backend solution for summarizing YouTube video transcripts. The API processes well-formatted closed captions and returns concise text summaries. Includes a web interface for easy use.  

*Created in 2020*: A stepping stone in exploring Flask and text summarization—remembering the journey from where it all began! 

---

## Features  
- Processes transcripts from YouTube videos with properly formatted closed captions.  
- Summarizes text efficiently using back-end API calls.  
- Includes a web interface for accessing the summarizer.

   
---

## Technologies Used  
- **Framework**: Flask  
- **Languages**: Python  
- **Other Tools**: Web hosting for the summarizer  

## Getting Started  
1. **Clone the Repository**  
   ```bash
   git clone <repository-link>



## Install Dependencies
Use `pip` to install the required packages:
```bash
pip install -r requirements.txt
```

## Run the Application
```bash
python app.py
```
The application will be hosted locally at http://127.0.0.1:5000/.


## How It Works
1.The backend receives API calls with a YouTube video URL.

2.Extracts and processes the video's closed captions.

3.Applies summarization logic to return a concise text summary.

4.Outputs the summary via API response or web interface.

## Limitations
- Works only on videos with well-formatted closed captions.

 - Summarization quality depends on transcript formatting.

## Future Scope
- Support for multilingual captions.

- Improved NLP techniques for summarization.

- Modern UI enhancements for the web version.

## License
MIT License—feel free to use and modify.

## Acknowledgments
A heartfelt remembrance of the journey begun in 2020 and the passion that fueled this creation.



