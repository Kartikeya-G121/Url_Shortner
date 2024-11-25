# README: URL Shortener with Python and Flask  

## Project Overview  
This project is a simple **URL Shortener** built using **Python** and the **Flask** web framework. It allows users to input a long URL and get a shortened version. Users can then share or use the shortened URL to be redirected to the original link.

---

## Features  
- **Generate Short URLs**: Converts long URLs into shorter, easily shareable links.  
- **Redirect to Original URL**: Shortened URLs redirect users to the original website.  
- **Customizable Short Links (Optional)**: Users can optionally define their custom alias.  
 

---

## Prerequisites  
1. **Python 3.x**  
2. Flask Library: Install via pip  
   ```bash
   pip install flask
   ```  
3. Optional: Install **SQLite** or other database packages if needed.  

---

## Usage  
1. **Shorten a URL**: Enter a long URL in the input field and click "Shorten".  
2. **Custom Alias** (optional): Specify a custom alias for your short URL.  
3. **Share the Short Link**: Copy the generated short link and share it.  

---

- **Redirect to Original URL**  
  `GET /<short_url>`  

---

## Future Enhancements  
- Add **user authentication** for managing personal URLs.  
- Support **custom domains** for shortened URLs.  
- Implement **advanced analytics** with charts and export options.  
- Enable **QR code generation** for shortened URLs.  
