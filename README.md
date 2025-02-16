# Streamlit App with Docker

## Run Locally in VS Code

1. **Install Dependencies**
   ```sh
   pip install -r requirements.txt
   ```
2. **Run the Streamlit App**
   ```sh
   streamlit run streamlit.py
   ```
3. Open the provided local URL in your browser.

## Run with Docker

1. **Build the Docker Image**
   ```sh
   docker build -t streamlit-app .
   ```
2. **Run the Docker Container**
   ```sh
   d
   ```
3.

View build details: docker-desktop\://dashboard/build/desktop-linux/desktop-linux/o7sl1gqnkehr5wy1cmb0g4fqv

4. Open [http://localhost:8501](http://localhost:8501) in a browser.
  
5. Screenshots:
![image](https://github.com/user-attachments/assets/8fa33af5-cf52-4c14-8b98-133010b436ed)
![image](https://github.com/user-attachments/assets/d2dcf25f-7e17-4d35-90a8-290dc6fa4be3)


## File Structure

```
.
├── Dockerfile
├── main.py
├── requirements.txt
├── streamlit.py
```

- `Dockerfile` - Configuration for building the Docker container
- `main.py` - Python script with basic output
- `requirements.txt` - List of dependencies
- `streamlit.py` - Streamlit application script

