# secure-file-storage-using-hybrid-cryptography Using Python3
## Objective: To Achieve a secure plateform for storing of files on Cloud using Hybrid Cryptography
To achieve the above goal, the following methodology needs to be followed:

Load the file on the server.
Dividing the uploaded file into N parts.
Encrypting all the parts of the file using any one of the selected algorithms (Algorithm is changed with every part in round robin fashion).
The keys for cryptography algorithms is then secured using a different algorithm and the key for this algorithm is provided to the user as public key.
After the above 4 steps you will have a N files which are in encrypted form which are stored on the server and a key which is downloaded as public key for decrypting the file and downloading it.

To restore the file, follow the following steps:

Load the key on the server.
Decrypt the keys of the algorithms.
Decrypt all the N parts of the file using the same algorithms which were used to encrypt them.
Combine all the N parts to form the original file and provide it to the user for downloading.

## How to Run


Step 1: Install Requirements
pip install -r requirements.txt

Step 2: Run the application
python app.py

Step 3: Visit the localhost from your browser

Step 4: Enjoy :)

THE PROJECT HAS ENCOUNTERED A BUG BECAUSE OF THE CRYPTOGRAPHY LIBRARY BEING UPDATED. IF YOU ARE INTRESTED IN COLLABORATING TO IMPROVE THIS PROJECT FEEL FREE TO CONTACT ME :

ASIF- asifsahaa6@gmail.com
