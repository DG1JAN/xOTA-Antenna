# xOTA-Antenna
**A pcb for end fed antennas (EFHW, random wire) for SOTA, POTA,... xOTA** <br /><br />
maximum power rating:
* FT-140-43: 100W SSB/CW or 50W FT8 (etc)
* FT-114-43: 25W SSB/CW or 10W FT8 (etc)
* FT-82-43: 10W SSB/CM or 5W FT8 (etc)
<br />

![alt text](https://github.com/DG1JAN/xOTA-Antenna/blob/main/xOTA_3d_1.1.png)

![alt text](https://github.com/DG1JAN/xOTA-Antenna/blob/main/xOTA-Antenna_example.jpg)
(*the two bottom pictures are from the prev. proto desig (labeled as "EFHW" instead of "xOTA-Antenna") and Version 1.0.


## BOM (1:49 UnUn for EFHW*)
*The PCB can also be used with other UnUn windings (like 1:9) to build non resonant ("random wire") endfed antennas.
(links to Distributors are only examples)

1x PCB: custom order from PCB manufacturer e.g. from https://www.jlcpcb.com or https://aisler.net/

*here you can find the gerber files as ZIP-Archive: https://github.com/DG1JAN/xOTA-Antenna/blob/main/xota-gerber.zip <br />
Manuel (Dl2MAN) has made a good video to explain the ordering process for JLCPCB and Aisler: https://www.youtube.com/watch?v=1b3oLp7s9gk&t=202s*

1x Torroid	- e.g. FT140-43, Fair-Rite	5943001001 (AKA Amidon FT114-43) or FT82-43 [with reduced power rating])	
https://www.digikey.de/de/products/detail/fair-rite-products-corp/5943001001/8599631?s=N4IgTCBcDaIKwE4AsBmADGgjBzg4AgAQgC6AvkA

1x BNC Socket - Molex	731385033	(Hint: Using alternative Parts might be possible, take care about clearance between PCB and BNC-Plug (most BNC-Sockets are lower, so you cant connect a plug to the socket when soldert on PCB)
https://www.digikey.de/de/products/detail/molex/0731385033/1465137?s=N4IgTCBcDaKHAEAGA7AZgIwoBwFYEpXCALoC%2BQA

1x 100pF 1kV Ceramic Capaciator - e.g. Kemet	C333C101KDG5TA	
https://www.digikey.de/de/products/detail/kemet/C333C101KDG5TA/6161481?s=N4IgTCBcDaIMwE4EFoCMAWA7OlA5AIoHAEABCALoC%2BQA

1 meter Trafo wire - e.g. BLOCK	CUL 100/0,63mm (for 100W Version better 1mm)	
https://www.reichelt.de/100g-kupferlackdraht-auf-spule-0-63mm-cul-100-0-63-p57183.html?&nbc=1

2x 4mm Banana Socket - e.g.	GTIWUNG	4mm Plug	(In alternativ/addition to the Banana Sockets, you can also use 3mm Screws with Wingnuts for Antenna (and Ground radial - if so)
https://www.amazon.de/GTIWUNG-Vergoldete-Bananenstecker-Elektronische-Kugelstecker/dp/B07VYSN74H?pd_rd_w=O7WLe&content-id=amzn1.sym.995b3ade-87fd-4685-9950-c7995e7b483c&pf_rd_p=995b3ade-87fd-4685-9950-c7995e7b483c&pf_rd_r=1C95B6TWM7XGFV1X0J87&pd_rd_wg=sJWhQ&pd_rd_r=1c436703-eaf7-4adf-8249-24d57eab1f05&pd_rd_i=B07VYSN74H&psc=1&ref_=pd_bap_d_rp_1_i

8 cm Shrink tube 40mm wide - e.g. ISOLATECH	Shrink Tube 40mm  3:1 with glue	
https://www.amazon.de/gp/product/B06WVCGD7M/ref=ppx_yo_dt_b_asin_title_o09_s01?ie=UTF8&psc=1

---------------------

Take care about clearance between PCB and BNC-Plug (most BNC-Sockets are lower, so you cant connect a plug to the socket when soldert on PCB), use  Molex	"731385033" or similar.	 
![alt text](https://github.com/DG1JAN/xOTA-Antenna/blob/main/BNC_Socket.png) 

