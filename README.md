

  ```
  sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 
  ```
  ```
  apt update -y
  ```
  ```
  apt install git -y
  ```
  ```
  apt install python3-pip -y
  ```

* ## Edit File
 * search.txt
 * urls.txt

 
* ## Installation

  First, make sure you have installed git and Python version between 3.7.x to 3.9.x
  
  Open command prompt and type
  ```
  git clone https://github.com/minz18/YouTube-Viewer.git --depth 10
  ```
  ```
  cd YouTube-Viewer
  ```
  ```
  python -m pip install --upgrade pip wheel
  ```
  ```
  pip install "setuptools<59"
  ```
  ```
  pip install -r requirements.txt
  ```
  ```
  python proxy_check.py
  ```
  ```
  python youtube_viewer.py
  ```

# Linux / Mac
* ## Installation

  First, make sure you have installed git and Python version between 3.7.x to 3.9.x
  
  Open your favourite terminal and run
   ```
  git clone https://github.com/minz18/YouTube-Viewer.git --depth 10
  ```
  ```
  cd YouTube-Viewer
  ```
  ```
  python3 -m pip install --upgrade pip wheel
  ```
  ```
  pip3 install "setuptools<59"
  ```
  ```
  pip3 install -r requirements.txt
  ```
  ```
  python3 youtube_viewer.py
  ```
  ```
  python3 proxy_check.py
  ```

   * After closing program, if chromedrivers are still running. Open your terminal and run 
      ```bash
      ps aux | awk '/chrome/ { print $2 } ' | xargs kill -9
      ```
