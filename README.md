# DestructiveFarm-FlagStealer
A script that finds a [Destructive farms](https://github.com/DestructiveVoice/DestructiveFarm) with a defualt password and steals flags from them. For A/D CTF's.
# Usage
First of all clone this repo to the your client farm directory.

``` git clone https://github.com/lnfin/DestructiveFarm-FlagStealer```  

To find ip of vulnerable farms just start **check_ips.py** with number of teams in your network.  

``` ./check_ips.py <NUMBER_OF_TEAMS>```  

After the script finishes working start the file **sploit.py**. To run the file use this command:  

``` ./start_sploit.py sploit.py --not-per-team```  
