# LaravelP-D-

## Teorija

kas ir API?
API ir veids, kā divas vai vairākas programmas vai komponenti var sazināties savā starpā.

kā deklarēt mainīgo PHP mainīgo?
$mainiga_nosaukums = vērtība

Kādu arhitektūru izmanto Laravel?
Laravel izmanto Model-View-Controller arthitektūru.
Modelis atbild par datu pārvaldību, sazinās ar datubāzi un veic datu ieguvi.
Skats(View) nodrošina skatu un attēlo datus.
Controller saņem pieprasījumus no lietotāja, apstrādā datus un sazinās ar modeli, lai iegūtu vai mainītu datus.

Kas ir ORM, kāpēc to izmanto tīra SQL vietā?
ORM ir paņēmiens, kas ļauj vaicāt un manipulēt ar datiem no datu bāzes, izmantojot objektorientētu paradigmu.
Tas tiek izmantots, jo tas ļauj strādāt ar datiem kā ar objektiem, kas uzlabo koda izskatu.

Uzraksti Eloquent ORM pieprasījumu modelim User, kur nepieciešams iegūt visus
lietotājus kuriem reitings ir lielāks par 4. 

$Users = Users::where('rating','>',4)->get();
