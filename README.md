# RepoFilesPublic
PAra publicar files
#Nrok
4WTASX4UXS
2SJ3956KHJ
XJV2BS6PYJ
M3ZFPTD6TW
ME423DSSZT
MYRN7ZN3F3
KG4PFJVEEP
CRC46T9AHY
SGNVQBDBYP
VDPSGPGTCF
api:

-----------------------------------------------------
$apiUrl = 'http://<IP_SERVIDOR>:3000/serial-data';

// Solicitud GET a la API
$response = file_get_contents($apiUrl);
$data = json_decode($response, true);

if (isset($data['data'])) {
    echo "Dato recibido: " . $data['data'];
} else {
    echo "No se recibieron datos.";
}
?>
-----------------------------------------------------
