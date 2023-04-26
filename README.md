ExchangeDataScrape pulls exchanges and level 1 financial data in a two step process.

The first step requires StockSymbol API which can be found here: 

https://stock-symbol.herokuapp.com/

StockSymbol was created by Yongthong Tan and is licensed by MIT and is accessible on Python3.7 and higher 

As of version0.0.5, all listings were last updated on 2022-01-10

Package information can be found here: 

https://pypi.org/project/stocksymbol/

The second step is to pull all listed symbols within the desired market/index and scrape financials via yfinance.

Markets Available:


Index Available:
id: XETR:MDAX, name: MDAX PERFORMANCE-INDEX
id: TVC:UKX, name: UK 100 INDEX
id: TVC:SXXP, name: STOXX 600
id: TVC:SXXP, name: STOXX 600
id: TVC:SXXP, name: STOXX 600
id: TVC:SXXP, name: STOXX 600
id: TVC:SX5E, name: STOXX 50
id: TVC:STI, name: STRAITS TIMES INDEX
id: TVC:NI225, name: NIKKEI 225
id: TSX:TSX, name: S&P/TSX COMPOSITE INDEX
id: TASE:TA35, name: TA-35
id: SET:SET100, name: SET100 INDEX
id: OMXVSE:OMXVGI, name: OMX VILNIUS GI
id: OMXSTO:OMXS30, name: OMX STOCKHOLM 30 INDEX
id: OMXRSE:OMXRGI, name: OMX RIGA GI
id: OMXICE:OMXI10, name: OMX ICELAND 10
id: OMXHEX:OMXH25, name: OMX HELSINKI 25
id: OMXCOP:OMXC25, name: OMX COPENHAGEN 25 INDEX
id: NZX:NZ50G
id: NSE:NIFTY, name: NIFTY 50
id: MOEX:MOEXEU, name: MOEX ELECTRIC UTILITIES INDEX
id: INDEX:FTSEMIB, name: FTSE MIB INDEX
id: HSI:HSI, name: HANG SENG INDEX
id: EURONEXT:PX1, name: CAC 40
id: EURONEXT:PSI20, name: PSI 20
id: EURONEXT:BEL20, name: BEL 20
id: BMFBOVESPA:IBXL, name: IBRX 50
id: BIST:XUTUM, name: BIST TUM
id: BCBA:IMV
id: ASX:XJO, name: S&P/ASX 200
id: XETR:TDXP, name: TECDAX TR
id: XETR:SDXP, name: SDAX PERFORMANCEINDEX
id: XETR:DAX, name: DAX INDEX
id: TVC:SXXP, name: STOXX 600
id: TVC:SXXP, name: STOXX 600
id: TVC:SXXP, name: STOXX 600
id: TVC:SXXP, name: STOXX 600
id: TVC:SXXP, name: STOXX 600
id: TVC:SXXP, name: STOXX 600
id: TVC:SXXP, name: STOXX 600
id: TVC:SXXP, name: STOXX 600
id: TVC:SXXP, name: STOXX 600
id: TVC:SXXP, name: STOXX 600
id: TVC:SX5E, name: STOXX 50
id: TVC:SX5E, name: STOXX 50
id: TVC:SX5E, name: STOXX 50
id: TVC:SX5E, name: STOXX 50
id: TVC:SX5E, name: STOXX 50
id: TVC:SX5E, name: STOXX 50
id: TASE:TA125, name: TA-125
id: SZSE:399001, name: SHENZHEN COMPONENT INDEX
id: SET:SET50, name: SET50 INDEX
id: NSE:BANKNIFTY, name: NIFTY BANK
id: MOEX:RUBMI, name: RTS BROAD MARKET INDEX
id: MOEX:RTSI, name: RTS INDEX
id: MOEX:RTSCH, name: RTS CHEMICALS INDEX
id: MOEX:MOEXTN, name: MOEX TRANSPORT INDEX
id: MOEX:MOEXTL, name: MOEX TELECOMMUNICATION INDEX
id: MOEX:MOEXMM, name: MOEX METALS AND MINING INDEX
id: MOEX:MOEXINN, name: MOEX INNOVATION INDEX
id: MOEX:MOEXFN, name: MOEX FINANCIALS INDEX
id: MOEX:MOEXCN, name: MOEX CONSUMER INDEX
id: MOEX:MOEXCH, name: MOEX CHEMICALS INDEX
id: MOEX:MOEXBMI, name: MOEX BROAD MARKET INDEX (RUB)
id: MOEX:MOEX10, name: MOEX 10 INDEX
id: MOEX:MCXSM, name: MOEX SMID INDEX
id: MOEX:IMOEX, name: MOEX RUSSIA INDEX
id: EURONEXT:AEX, name: AEX-INDEX
id: BSE:SENSEX, name: S&P BSE SENSEX
id: BMFBOVESPA:IFIX, name: IND FDO IMOB
id: BMFBOVESPA:IBOV, name: BOVESPA INDEX
id: BIST:XUTEK, name: BIST TEKNOLOJI
id: BIST:XU100, name: BIST 100
id: BIST:XU050, name: BIST 50
id: BIST:XU030, name: BIST 30
id: BIST:XSPOR, name: BIST SPOR
id: BIST:XGIDA, name: BIST GIDA ICECEK
id: BIST:XBANK, name: BIST BANKA
