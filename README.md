# dotapps.io

The apps UI served via IPNS with dnslink. 

This site, deployed at https://dotapps.io just performs a redirect to the latest IPFS hash, as served via IPNS on https://ipfs.io/ipns/dotapps.io

In addition to the default ipfs.io gateway, alternatives are also provided (these are all ipns capable) -

- https://cloudflare-ipfs.com/ipns/dotapps.io
- https://gateway.ipfs.io/ipns/dotapps.io
- https://gateway.pinata.cloud/ipns/dotapps.io
- https://gateway.temporal.cloud/ipns/dotapps.io
- http://localhost:5001/ipns/dotapps.io

The above can be expanded based on user-preferences and feedback. In addition, a reverse lookup on the ipns name is done to retrieve the latest hash. If this is resolved, it is listed as a local link.
