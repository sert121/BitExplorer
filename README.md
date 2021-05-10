# BitExplorer
This application allows exploration of the BTC Testnet ledger, by offering different features not currently available at other BTC explorers.


## Installation
For setting up a full bitcoin node, please refer [BTC Core](https://bit.ly/3hg2TMy).  
For a video-demo of the setup please refer [[1]](https://drive.google.com/file/d/1FJwqIkqRVJ71aikOYbtEe5acMh3zFg4_/view?usp=sharing)  
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install BitExplorer.

```bash
pip install requirements.txt
```
### Features

- Detection of a valid hash of a ```block``` or ```transaction```
- Compute specific block/txn details such as
  * Address types
  * Output type
  * Transaction type( Regular/ Non-regular)
- Compute the above details for a range of blocks
  * The range can be entered via block height
  * The range can also be specified via date range
- JSON formatted block and transaction details for any ```block/tx```

## Usage
The web interface is available at : [[2]](http://206.189.131.95:8501/)  
To locally run the project: ```streamlit run toc.py```
A demo of of the interface and its usage can be found here[[3]](https://drive.google.com/file/d/1pgz_9rawK219MLb1qTkd9IHy-2N0SKTw/view?usp=sharing)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
