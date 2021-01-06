# API-s on Views

## HOME

- Home screen
  - statuses (verification)
  - recieved surpluses
  - personal orderbook summary
  - priviledges: 
    - buy/sell
    - addMeter
  - GDP
    - points
  - News (top list)


## TRADING

### LIMIT ORDER

- orderbook
- timeslot dropdown
- personal deals
- calculate
- order history

### ADD METER

- šifranti
  - contract type
  - distributor (autocomplete)
  - postcode
- what to buy
- suggest
- estimate savings (post choice)
- 


https://plnkr.co/edit/Cw90urvr3TkodtOP2Ru8?p=preview&preview
     

Vprašanja:
- zakaj Buy/Sell, če izbiraš meter? A lahko preprodajaš elektriko, ki si jo kupil na svojem metru? Zakaj ne izbereš meter (Producer, Consumer), pa se potem postaviš na ustrezen trg? 
- Zakaj nimamo pri Sell tudi balance, koliko elektrike imaš na voljo za prodat? Kako vemo (oz. kako suncontract ve), da je ta elektrika na voljo?
- A bodo res vedno in strogo ločeni orderbooki po mesecih? A ko prodajaš, moraš potem za vsak mesec postavit order? A imaš kvote za balance elektrike na mesec? 
- Če si consumer imaš verjetno anti-balance (estimated), t.j. kolikom moraš/smeš zapolnit priključek? Glede na to, da vemo tvoj "need"?
- Kaj pomenijo barve na orderbooku? Kaj je namen orderbooka? Kako se scrolla/expanda?
- Označevanje hkrati metra in meseca z enim dropdownom je nepraktično. Če imaš en meter, rabiš samo mesece. Če pa imaš več metrov in veliko trguješ, je nepraktično, ko pri istem obdobju (izbor več mesecev) preklapljaš med metri. Izbore mesecev bi bilo bolj smiselno imeti ločeno. Dopuščal bi samo intervale mesecev.
- Suggest bi bilo bolje, da je average price for market order za izbrano obdobje. Potem je brezveze izpisovat vnosno polje za average price.
- Če nisi v Limit orderjih ne rabiš celega orderbooka ampak samo ponudbo.
- Če cena, ki jo postaviš bistveno odstopa od marketa (npr. se zatipkaš za eno nulo) bi te moralo opozoriti


