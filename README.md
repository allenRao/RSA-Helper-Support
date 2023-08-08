# RSA-Helper-Support	
RSA helper support	
Issue open	

allen.rao2011#gmail.com (email, replace # with @)

RSA Helper focuses on data encryption, does not connect to the Internet, and stores the encrypted data locally.
When to tell your family members the bank card password via text message, send it after encryption to prevent the password from being leaked.
When to send a private message to your girlfriend through WeChat, send it after encryption to ensure privacy and security.
When to send confidential files to colleagues through QQ, send them after encryption to prevent file leakage.
This application uses the RSA asymmetric encryption algorithm, which can encrypt messages, photos, videos, and files.

Assume that user A and user B plan to have encrypted communication through WeChat.
User A creates his own key pair locally, including public key a and private key a.
User B also creates his own key pair locally, including public key b and private key b.
Then A and B exchange public keys through WeChat, and save each other's public keys.
User A uses private key b to encrypt the message into ciphertext, and the ciphertext is sent to user B via WeChat.
User B decrypts the ciphertext with his own private key b.
User A and user B can also use the same method to encrypt files for transmission.

The main features:
	Message decryption:
		Create your own RSA key pair, public key and private key;
		Copy your own public key and share it with the others;
		Decrypt the message with your own private key.
	Message encryption:
		Storage and management of the others’ public keys;
		Encrypt the message using the other's public key.
	File decompression, encryption and decryption:
		Compression of files, decompression of zip files;
		Use the other's public key to encrypt files;
		ziprsa is the encrypted file extension.
		Use your own private key to decrypt the ziprsa files;
	Local LAN file transfer:
		Open file web server , upload, download within local LAN.
	Message Encryption Extended Keyboard:
		Select the public key of the other;
		encrypt the text in the input box, and send it;
		Use your own public key to decrypt the ciphertext in the pastboard;
		Send your own public key to the others;




