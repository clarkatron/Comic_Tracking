# Comic_Tracking
Web-Crawler and DB

User Tables:



Book Tables:
UUID [String]
Last 5 Owners [String]x5

User Facing:
	Title [String]
	Publisher [String]x5
	Images [.imgs]x5

	Issue [Int]
	Variant [Bool]
	Variant Type [String]
	Date Published [String]

	Script/Writer [String]x5
	Pencils [String]x5
	Inks [String]x5
	Colors [String]x5
	Letters [String]x5

	Genre [String] x3
	Characters[String]x20

Pricing:
	Averaging window size [Int]
	Average Ebay Sold Price [Float]
	Average "Oursite" Sold Price [Float]

From user space:
User can scan UPC or take image of cover of book. 
This will then autopopulate user facing items in table. User will be 
asked if they want to add to their collection or price check.

Price check will bring up pricing info. 

Add to collection will bring up new options. It will autopopulate the 
book into the correct series and will then check off 
