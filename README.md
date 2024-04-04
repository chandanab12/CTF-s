# CTF-s

A quick cheat sheet to participate in CTF's 

# OSINT

## Image Analysis

To find the geolocation of an image or metadata - Use ExifTool
1. (https://exif.tools/upload.php)
2. (https://www.pic2map.com/) For location

Kali Commands
- file (filename).jpg
- exiftool (filename)
- xxd (filename)
- strings (filename) | to find strings in a file
- binwalk (filename) | enables you to search binary images for embedded files and executable code
- binwalk -e (filename) | to find hidden files

Barcode Interpretor (https://online-barcode-reader.inliteresearch.com/)

[StegTool](https://georgeom.net/StegOnline/checklist)


## WHOIS Lookup 

- [WHOIS Lookup](https://www.whois.com/whois/)
  Allows you to look into information about a domain name of an ip address

## PGP Keys

(https://keys.openpgp.org/) To look for KEY ID or Fingerprints


(http://keyserver.ubuntu.com/) To also check for key creation and expiry times


(http://pgp.mit.edu/)

# Crypto 

- [CyberChef](https://gchq.github.io/CyberChef/)

- [CaeserCipher Decoder](https://cryptii.com/pipes/caesar-cipher-decoder)

- [Dcode](https://www.dcode.fr/tools-list) Cipher Identifier

- [Boxentriq](https://www.boxentriq.com/)  Code breaker, cipher identifier, puzzle solver

- 

# Network Analysis

Kali Commands:
- dig (domain name)


# Forensics

To analyze a zip file  | unzip filename
ls commands 
- ls -l
- ls -la 

If there is a .git repository, we can leverage git commands to find out more about the commits and extract information


git log | To check the commits 


git show (commit details) | to check a particular commit

git branch | to check all other possible branches 

git checkout (branch_name) | to move to a particular branch 
