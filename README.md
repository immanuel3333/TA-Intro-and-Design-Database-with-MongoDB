<h1>Soal nomor 1</h1>
{
"_id": "ObjectId('AAA')",
"full_name": "Immanuel Julius Adik Putra Siburian",
"email": "immanuel.siburian80@gmail.com",
"phone_number": 081212313515
}

<h1>Soal nomor 2</h1>
<h2>Relasi one to many</h2>
{
    "_id": "ObjectId('AAA')",
    "full_name": "Immanuel Julius Adik Putra Siburian",
    "phone_mumber": 081212313515
    "address": [
        "ObjectId('XYZ')",
        "ObjectId('LMN')",
    ]
}

<h1>Soal nomor 3</h1>
<h2>Relasi one to many</h2>
{
    "_id": "ObjectId('AAA')",
    "product_name": "Kaos Polos",
    "brand_name": "SkilShirt",
    "variant": [{
        "_id": "ObjectId('XYZ')",
        "variant_name_1": "Kaos Polos Hitam",
        "color": "Hitam",
        "quantity": 12,
        "price": "Rp 99.000",
    },{
         "_id": "ObjectId('LMN')",
        "variant_name_1": "Kaos Polos Navy",
        "color": "Navy",
        "quantity": 10,
        "price": "Rp 99.000",
    }]
}

<h1>Soal nomor 4</h1>
<h2>Relasi one to many</h2>
[
    {
    "_id": "ObjectId('AAA')",
    "cinema_name": "CGF",
    "film": [
        "ObjectId('Venom 2')",
        "ObjectId('Spiderman No Way Home')"
    ],
    "location": "Pondok Indah Mall"
    },
    {
    "_id": "ObjectId('BBB')",
    "cinema_name": "Cinema 31",
    "film": [
        "ObjectId('Venom 2')",
        "ObjectId('Spiderman No Way Home')"
    ],
     "location": "Mall Kelapa Gading"
    }
]
