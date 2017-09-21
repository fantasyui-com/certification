# certification
Stateless Ownership of Digital Goods

When a customer makes a purchase, do not store data on the server, rather give the customer a unique tamperproof Download Certificate for downloading and re-downloading the purchased product.

The first and foremost is customer email and name as verified by a payment processor, without that information the certificate will not be unpacked.

Fronting customer email and name will discourage the customer from sharing the digital download certificate.

Certificate may be re-issued upon a re-download, meaning that an older certificate may be invalidated by passage of time.

--

- Upon a purchase, user is given a hard to modify/decrypt text string, called certificate.
- The header of the certificate contains a hash.
- The body of the certificate contains data encrypted with a server-side key.
- Body can be decrypted on the server.
- Decryption keys can be changed, older keys can be used.
- Certificates can expire.
- Certificates can be re-issued.
- Certificates are never stored on the server, they are given to the user/client, may not even be emailed.

- The server can be erased and no data-loss will occur; customers with valid certificates can re-download their purchased data.