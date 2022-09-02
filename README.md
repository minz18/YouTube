

  ```
  sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 4EB27DB2A3B88B8B
  apt update
  apt upgrade -y

  ```

  ```
  apt install git -y && apt install python3-pip -y

  git clone https://github.com/minz18/YouTube.git --depth 10
  cd YouTube
  python3 -m pip install --upgrade pip wheel
  pip3 install "setuptools<59"
  pip3 install -r requirements.txt
  python3 youtube_viewer.py

  ```

   * After closing program, if chromedrivers are still running. Open your terminal and run 
      ```bash
      ps aux | awk '/chrome/ { print $2 } ' | xargs kill -9
      ```
