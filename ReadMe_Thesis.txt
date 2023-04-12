
I am doing a project as a part of my job, and thus working with both personally sensitive and confidential data.
(I’m working on micro-level transaction data reported to the S-FSA under MiFIR).
Hence, I am unable to share the underlying data, but am able to share the graphs and code. 
As I am unable to share the data used in this study, I present the information contained in the datafiles used. 

DispEff_raw
id: Id of original File
TradeDate_date: Timestamp of transaction
PersID: Personal Identification of the individual
nRealGains: Number of Gains sold at time t
nRealLoss: Number of losses sold at time t
nPaperGains: Paper gains in portfolio at time t
nPaperLoss: Paper losses in portfolio at time t
shrExtremeUp: Shr of portfolio that experiance > +3 s.d. move
shrExtremeDown: Shr of portfolio that experiance < -3 s.d. move


DispDeets_dat
id: Id of original File                   
TradeDate_date: Timestamp of transaction
PersID: Personal Identification of the individual
FinancialInstrumentISIN: ISIN of traded instrument
QtyHeld: Quantity of instrument held
Avr_AdjPrice: Average FX-adjusted price paid for instrument for day t
QtyTraded: Quantity of instrument traded at time t
Is_RealizedOrPaper: Categorical, Relized of Paper
Realized_Price: Price at time of transaction
CumAvrAdjPrice: Average Price paid for instrument up to day t-1
Price_AdjFxAdj: Transaction price at end of day
yDayPriceMove: Price move compared to yday
ref_PriceAdj: Price move yday to day close
Realized: Boolean, if realized
Paper: Bollean, if paper
zScore: Price move compared to 250day moving t-dist
PrevDayPrice: Price y-day
ValueOfHolding: Value of position
Value_IsExtreme_Up: Value of position, if extreme up
Value_IsExtreme_Down: Value of position, if extreme down
Realized_IsExtreme_Up: Boolean, if extreme up realized
Realized_IsExtreme_Down: Bollean, if extreme down realized
IsRealized_yDayGain: Boolean, was yday gain
IsRealized_yDayLoss: Boolean, was yday loss
LastPurchaseDate: Date of last purchase
DaysSinceLastPurchase: Days since last purchase
BUY_VAL: Value of purchase
SELL_VAL: Value of selling
ValuePortfolio: Value of portfolio at time t



Overtrading_Dat
id: Id of original File 
Identification: Personal Identification of the individual
PersID_Side: Selling or Buying
FinancialInstrumentISIN: ISIN of relvant instrument
nTrades: number of trades in said instrument
TotTurn: Turnover in instrument in EUR
AvrValueTrade_EUR: Average traded value in EUR

      
Diversification_Dat
id: Id of original File 
Identification: Personal Identification of the individual
FinancialInstrumentISIN: ISIN of relvant instrument
nTrades: number of trades in said instrument
TotTurn: Turnover in instrument in EUR
AvrValueTrade_EUR: Average traded value in EUR
      
Descriptive_Dat
id: Id of original File 
Identification: Personal Identification of the individual
AssetClass: Asset class according to CFI-code
Period: Timestamp of trading
nTrades: number of trades in said instrument
TotTurn: Turnover in instrument in EUR
AvrValueTrade_EUR: Average traded value in EUR


HomeBias_Dat
id: Id of original File 
Identification: Personal Identification of the individual
RelevantCompetentAuthority: FSA resposnible for instrument
CountryISIN: Domicile of ISIN
nTrades: Number of trades in instrumen
TotTurn: Turnover in instrument in EUR
AvrValueTrade_EUR: Average traded value in EUR


















