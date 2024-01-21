# whatsapp
whatsapp sender  free


```bash
apt install unzip
cd whatsapp
unzip node_modules.zip
```

## php curl

```bash
<?php

$curl = curl_init();

curl_setopt_array($curl, array(
  CURLOPT_URL => 'http://localhost:8000/send-message',
  CURLOPT_RETURNTRANSFER => true,
  CURLOPT_ENCODING => '',
  CURLOPT_MAXREDIRS => 10,
  CURLOPT_TIMEOUT => 0,
  CURLOPT_FOLLOWLOCATION => true,
  CURLOPT_HTTP_VERSION => CURL_HTTP_VERSION_1_1,
  CURLOPT_CUSTOMREQUEST => 'POST',
  CURLOPT_POSTFIELDS => array('message' => 'oke','number' => '081252053793','file_dikirim'=> new CURLFILE('/C:/Users/Nusantara/Documents/Laporan Buku Tamu Tanggal 01-9-2022.pdf')),
));

$response = curl_exec($curl);

curl_close($curl);
echo $response;
```
