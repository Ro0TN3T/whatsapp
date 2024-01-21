# whatsapp
whatsapp sender  free


### Request
```bash
nodejs & npm
```

### usage :
```bash
git clone https://github.com/Ro0TN3T/whatsapp.git
cd whatsapp
npm i
node index.js
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
  CURLOPT_POSTFIELDS => array('message' => 'oke','number' => '081252053793','file_dikirim'=> new CURLFILE('![image](https://github.com/Ro0TN3T/whatsapp/assets/46824241/b7c83664-e761-43d4-9624-ebd9f6ef5aae)
')),
));


$response = curl_exec($curl);

curl_close($curl);
echo $response;
```

### untuk kirim pesan ke group  URL mengarah ke
```bash
http://localhost:8000/send-group-message
```

