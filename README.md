# Nova finance nToken program


Nova finance is building a range of assets, tools and strategies which allow people to manage and adjust their risk exposure to cryptocurrency.

Nova achieves this by providing hedging techniques and packaging them into tokens called nAssets. “Hedging” is a common technique used by experienced investors to reduce volatility and protect the value of their portfolio.

Through nAssets, people can easily adopt these hedging techniques and protect themselves from volatility while still getting exposure to cryptocurrency. The mainstream market finds it hard to adopt cryptocurrency because the high volatility can often result in a loss of investment. By providing greater control over volatility, it ensures:


This program provides an interface and implementation that third parties can
utilize to create and use our nToken.

Visit our site "https://novafinance.app/#/"



JavaScript binding are available in the `./js` directory.


<img src="https://github.com/NovaFi/nasset-solana-new/raw/main/nova-solanba.png" style="text-align: center;">


<video width="640" height="480" controls>
  <source src="https://github.com/NovaFi/NToken-solana/raw/main/demo.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

Test our project , follow the next steps

## Setup Guide 

### install rust 

```bash
$ curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

### install solana 

```bash
$ sh -c "$(curl -sSfL https://release.solana.com/v1.6.6/install)"
```


## Download the project 

```bash
$ git clone https://github.com/zdbrig/nToken-solana
```


To run our project , follow the next steps :

First fetch the npm dependencies,  by running:

```bash
$ npm install
```

There are two ways to build the on-chain program :

### first way

```bash
$ cd program
$ cargo build-bpf
```
### second way

```bash
$ cd js 
$ npm run build:program
```
 ## Run the client 

```bash
$ cd js
$ npm install
$ npm run start
```



