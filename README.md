# NepalTouristdata
- Webscraped and collected all the tourist data of Nepal from 1964 to 2019 

- All the data's are in the csv file

## Himalayan Data Subfolder
- All the data from himalayandatabase is stored here
- The rar files consists of all the compressed himalayan database df files. It is comprised of three separate tables, one for all the mountaineering peaks of Nepal, one for all the expeditions that have climbed in Nepal or on its border peaks, and one for the members of those expeditions.
- Click on the rar file and click 'View raw' to download it
- I have also added my SQL scripts to extract datas from the database relational tables and stored into csv files. SQL scripts are also available
#### The relationship between the DBF tables
<img width="619" alt="Screenshot 2022-04-02 at 15 23 01" src="https://user-images.githubusercontent.com/51405208/161377293-3204babb-6370-4985-8456-ba8c1479ce39.png">
The Peaks table describes the mountaineering peaks of Nepal, one record for
each peak. There are 468 records in this table.

- The Exped table describes each of the climbing expeditions. There are more
than 10,500 records in this table.

- The Members table describes each of the members on the climbing team and
hired personnel who were significantly involved in the expedition. There are
more than 78,400 records in this table.

- The Refer table describes the literature references for each expedition,
primarily major books and journal and magazine articles. There are more than
14,700 records in this table.

### Data Columns
#### Expeditions (exped.dbf)
Column Name	Data Type	Description
BCDATE	Date	Undocumented
O2CLIMB	Boolean	Undocumented
STDRTE	Unknown	Undocumented
PRIMREF	Unknown	Linked reference ID?
CAMPSITES	String	Comma-delimited list of campsite data
DISPUTED	Boolean	Whether the expedition is disputed
HOST	Integer	Undocumented
TOTDAYS	Integer	Total days of the expedition
PARAPENTE	Boolean	Undocumented
CHKSUM	Integer	Undocumented
COMRTE	Unknown	Undocumented
NATION	String	Nation listed with this expedition
CLAIMED	Boolean	Undocumented
YEAR	Integer	Year in which the expedition took place
TRAVERSE	Boolean	Undocumented
LEADERS	String	Name(s) of the leader(s) on this expedition
SMTDATE	Date	Undocumented
TERMDATE	Date	Termination date?
NOHIRED	Boolean	Undocumented
COUNTRIES	String	Countries related to this expedition
ACCIDENTS	Unknown	Undocumented
SUCCESS3	Boolean	Undocumented
SUCCESS4	Boolean	Undocumented
EXPID	String	Primary expedition ID
SUCCESS1	Boolean	Undocumented
HIGHPOINT	Integer	Highest elevation reached during this expedition
SUCCESS2	Boolean	Undocumented
MDEATHS	Integer	Number of member deaths
02MEDICAL	Boolean	Undocumented
CAMPS	Integer	Number of camps on this expedition
ROUTEMEMO	String	Undocumented
ROUTE3	String	Undocumented
ROUTE4	String	Undocumented
ROUTE1	String	Undocumented
ROUTE2	String	Undocumented
O2DESCENT	Boolean	Undocumented
O2SLEEP	Boolean	Undocumented
PRIMMEM	Boolean	Undocumented
O2NONE	Boolean	Undocumented
PEAKID	String	Linked peak ID
ROPE	Integer	Undocumented
TOTMEMBERS	Integer	Total number of members on this expedition
PRIMRTE	Boolean	Undocumented
SMTTIME	Integer	Undocumented
SMTDAYS	Integer	Undocumented
O2TAKEN	Boolean	Undocumented
ACHIEVMENT	Unknown	Undocumented
SPONSOR	String	Sponsor of the expedition?
SMTMEMBERS	Integer	Undocumented
TERMNOTE	String	Undocumented
APPROACH	String	Undocumented
OTHERSMTS	String	Undocumented
SMTHIRED	Integer	Undocumented
TOTHIRED	Integer	Total members hired?
PRIMID	Unknown	Undocumented
SEASON	Integer	Season code (unknown attribute values)
ASCENT1	String	Undocumented
SKI	Boolean	Whether or not this expedition had skis?
AGENCY	String	Agency associated with this expedition
HDEATHS	Integer	Undocumented
TERMREASON	Integer	Undocumented
O2UNKWN	Boolean	Undocumented
ASCENT4	Unknown	Undocumented
ASCENT3	Unknown	Undocumented
ASCENT2	Unknown	Undocumented

