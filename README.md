# AI Article Summarizer

This project is a web-based application that uses the [Article Extractor and Summarizer API](https://rapidapi.com/restyler/api/article-extractor-and-summarizer) to summarize articles. Users can input an article's URL, and the application provides a summarized version of the content.

## Getting Started

1. **Clone the Repository**:

   ```bash
   git clone <repository-url>
   cd ai_summarizer
   ```

2. **Install Dependencies**:

   ```bash
   npm install
   ```

3. **Setup Environment Variables**:

   - Rename `.env.sample` to `.env`.
   - Set `VITE_RAPID_API_ARTICLE_KEY` with your RapidAPI key.

4. **Run the Application**:
   ```bash
   npm run dev
   ```

## Structure

- `src/`: Contains the main application logic, components, and Redux slices.
- `public/`: Contains public assets like images and fonts.
- `index.html`: Main HTML file for the application.
- `vite.config.js`: Configuration file for Vite.js.
- `tailwind.config.js`: Configuration file for Tailwind CSS.

## API Rate Limits

If you encounter a "Too Many Requests" error (status code 429), it indicates that you've hit the rate limits set by the RapidAPI provider. Check the [RapidAPI documentation](https://rapidapi.com/restyler/api/article-extractor-and-summarizer) for details on rate limits.

## Security Note

Always keep your API keys and sensitive information secure. Do not expose them in public repositories or public forums. If you believe an API key has been compromised, regenerate it from the provider's dashboard.

## Further Development

To enhance this application, consider adding features like:

- Saving summaries to a database for persistence.
- Providing options for different summary lengths.
- Implementing user accounts and personalized summary histories.

## References

1. [Article Extractor and Summarizer API](https://rapidapi.com/restyler/api/article-extractor-and-summarizer)
2. [YouTube Tutorial](https://youtu.be/A6g8xc0MoiY?si=nBQ0oBk3guGBBjeS)
