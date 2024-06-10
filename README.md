fred>  db.computadores.insertMany([{Descricao: "Computador Dell Inspiron",Marca: "Dell",Modelo: "Ifred>  db.computadores.insertMany([{Descricao: "Computador Dell Inspiron",Marca: "Dell",Modelo: "Ifred>  db.comfred>  db.computadores.insertMany([{Descricao: "Computador Dell Inspiron",Marca: "Dell",Modelo: "Inspiron",Fabricacao: 2023,Configuracao:{Processador: "Intel i5",Memoria: "8 Gb", Disco: "HDD 500Gb",Monitor: "LED 19”",Teclado: "ABNT2",Mouse: "Óptico 2 Botões"},Programas: ["Windows 10", "Microsoft Office", "Avast Antivirus"], Aquisicao: "05/10/2024", Valor: 2500.00 }])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('6667092fe91f89cce86b837c') }
}
fred>
fred> db.fred.find()
fred> db.computadores.find()
[
  {
    _id: ObjectId('6667092fe91f89cce86b837c'),
    Descricao: 'Computador Dell Inspiron',
    Marca: 'Dell',
    Modelo: 'Inspiron',
    Fabricacao: 2023,
    Configuracao: {
      Processador: 'Intel i5',
      Memoria: '8 Gb',
      Disco: 'HDD 500Gb',
      Monitor: 'LED 19”',
      Teclado: 'ABNT2',
      Mouse: 'Óptico 2 Botões'
    },
    Programas: [ 'Windows 10', 'Microsoft Office', 'Avast Antivirus' ],
    Aquisicao: '05/10/2024',
    Valor: 2500
  }
]
fred> db.computadores.inserMany([{Descricao: "Computador HP Pavilion",Marca: "HP",Modelo: "Pavilion",Fabricacao: 2022,Configuracao: {Processador: "AMD Ryzen 7",Memoria: "16 Gb",Disco: "SSD 512Gb",Monitor: "LED 24”",Teclado: "ABNT2",Mouse: "Óptico 3 Botões"},Programas: ["Windows 11", "Office 365", "McAfee Antivirus"],Aquisicao: "15/05/2024",Valor: 3200.00}])
TypeError: db.computadores.inserMany is not a function
fred> show dbs
admin    40.00 KiB
banco    40.00 KiB
config  108.00 KiB
fred     40.00 KiB
local   104.00 KiB
test    100.00 KiB
vitor    72.00 KiB
fred> db.computadores.insertMany([{Descricao: "Computador HP Pavilion",Marca: "HP",Modelo: "Pavilion",Fabricacao: 2022,Configuracao: {Processador: "AMD Ryzen 7",Memoria: "16 Gb",Disco: "SSD 512Gb",Monitor: "LED 24”",Teclado: "ABNT2",Mouse: "Óptico 3 Botões"},Programas: ["Windows 11", "Office 365", "McAfee Antivirus"],Aquisicao: "15/05/2024",Valor: 3200.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('66670a29e91f89cce86b837d') }
}
fred> db.computadores.find()
[
  {
    _id: ObjectId('6667092fe91f89cce86b837c'),
    Descricao: 'Computador Dell Inspiron',
    Marca: 'Dell',
    Modelo: 'Inspiron',
    Fabricacao: 2023,
    Configuracao: {
      Processador: 'Intel i5',
      Memoria: '8 Gb',
      Disco: 'HDD 500Gb',
      Monitor: 'LED 19”',
      Teclado: 'ABNT2',
      Mouse: 'Óptico 2 Botões'
    },
    Programas: [ 'Windows 10', 'Microsoft Office', 'Avast Antivirus' ],
    Aquisicao: '05/10/2024',
    Valor: 2500
  },
  {
    _id: ObjectId('66670a29e91f89cce86b837d'),
    Descricao: 'Computador HP Pavilion',
    Marca: 'HP',
    Modelo: 'Pavilion',
    Fabricacao: 2022,
    Configuracao: {
      Processador: 'AMD Ryzen 7',
      Memoria: '16 Gb',
      Disco: 'SSD 512Gb',
      Monitor: 'LED 24”',
      Teclado: 'ABNT2',
      Mouse: 'Óptico 3 Botões'
    },
    Programas: [ 'Windows 11', 'Office 365', 'McAfee Antivirus' ],
    Aquisicao: '15/05/2024',
    Valor: 3200
  }
]
fred> db.computadores.insertMany([{Descricao: "Computador Lenovo ThinkCentre",Marca: "Lenovo",Modelo: "ThinkCentre",Fabricacao: 2023,Configuracao: {Processador: "Intel Core i3",Memoria: "4 Gb",Disco: "HDD 1Tb",Monitor: "LED 21.5”",Teclado: "ABNT2",Mouse: "Óptico 2 Botões"},Programas: ["Windows 10", "LibreOffice", "Avira Antivirus"],Aquisicao: "20/05/2024",Valor: 1800.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('66670ad8e91f89cce86b837e') }
}
fred> db.computadores.insertMany([{Descricao: "Computador Acer Aspire",Marca: "Acer",Modelo: "Aspire",Fabricacao: 2024,Configuracao: {Processador: "AMD Ryzen 5",Memoria: "12 Gb",Disco: "SSD 256Gb",Monitor: "LED 23.8”",Teclado: "ABNT2",Mouse: "Óptico 3 Botões"},Programas: ["Windows 11", "Microsoft Office", "Avast Antivirus"],Aquisicao: "03/05/2024",Valor: 2800.00 }])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('66670b50e91f89cce86b837f') }
}
fred> db.computadores.insertMany([{Descricao: "Computador Asus ROG Strix",Marca: "Asus",Modelo: "ROG Strix",Fabricacao: 2023,Configuracao: {Processador: "Intel Core i9",Memoria: "32 Gb",Disco: "SSD 2Tb",Monitor: "LED 27” 4K",Teclado: "ABNT2",Mouse: "Óptico 6 Botões" },Programas: ["Windows 11", "Adobe Creative Suite", "Norton Antivirus"],Aquisicao: "08/05/2024",Valor: 5000.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('66670bd3e91f89cce86b8380') }
}
fred> db.computadores.find()
[
  {
    _id: ObjectId('6667092fe91f89cce86b837c'),
    Descricao: 'Computador Dell Inspiron',
    Marca: 'Dell',
    Modelo: 'Inspiron',
    Fabricacao: 2023,
    Configuracao: {
      Processador: 'Intel i5',
      Memoria: '8 Gb',
      Disco: 'HDD 500Gb',
      Monitor: 'LED 19”',
      Teclado: 'ABNT2',
      Mouse: 'Óptico 2 Botões'
    },
    Programas: [ 'Windows 10', 'Microsoft Office', 'Avast Antivirus' ],
    Aquisicao: '05/10/2024',
    Valor: 2500
  },
  {
    _id: ObjectId('66670a29e91f89cce86b837d'),
    Descricao: 'Computador HP Pavilion',
    Marca: 'HP',
    Modelo: 'Pavilion',
    Fabricacao: 2022,
    Configuracao: {
      Processador: 'AMD Ryzen 7',
      Memoria: '16 Gb',
      Disco: 'SSD 512Gb',
      Monitor: 'LED 24”',
      Teclado: 'ABNT2',
      Mouse: 'Óptico 3 Botões'
    },
    Programas: [ 'Windows 11', 'Office 365', 'McAfee Antivirus' ],
    Aquisicao: '15/05/2024',
    Valor: 3200
  },
  {
    _id: ObjectId('66670ad8e91f89cce86b837e'),
    Descricao: 'Computador Lenovo ThinkCentre',
    Marca: 'Lenovo',
    Modelo: 'ThinkCentre',
    Fabricacao: 2023,
    Configuracao: {
      Processador: 'Intel Core i3',
      Memoria: '4 Gb',
      Disco: 'HDD 1Tb',
      Monitor: 'LED 21.5”',
      Teclado: 'ABNT2',
      Mouse: 'Óptico 2 Botões'
    },
    Programas: [ 'Windows 10', 'LibreOffice', 'Avira Antivirus' ],
    Aquisicao: '20/05/2024',
    Valor: 1800
  },
  {
    _id: ObjectId('66670b50e91f89cce86b837f'),
    Descricao: 'Computador Acer Aspire',
    Marca: 'Acer',
    Modelo: 'Aspire',
    Fabricacao: 2024,
    Configuracao: {
      Processador: 'AMD Ryzen 5',
      Memoria: '12 Gb',
      Disco: 'SSD 256Gb',
      Monitor: 'LED 23.8”',
      Teclado: 'ABNT2',
      Mouse: 'Óptico 3 Botões'
    },
    Programas: [ 'Windows 11', 'Microsoft Office', 'Avast Antivirus' ],
    Aquisicao: '03/05/2024',
    Valor: 2800
  },
  {
    _id: ObjectId('66670bd3e91f89cce86b8380'),
    Descricao: 'Computador Asus ROG Strix',
    Marca: 'Asus',
    Modelo: 'ROG Strix',
    Fabricacao: 2023,
    Configuracao: {
      Processador: 'Intel Core i9',
      Memoria: '32 Gb',
      Disco: 'SSD 2Tb',
      Monitor: 'LED 27” 4K',
      Teclado: 'ABNT2',
      Mouse: 'Óptico 6 Botões'
    },
    Programas: [ 'Windows 11', 'Adobe Creative Suite', 'Norton Antivirus' ],
    Aquisicao: '08/05/2024',
    Valor: 5000
  }
]
fred> db.computadores.insert([{Descricao: "Computador Apple iMac",Marca: "Apple",Modelo: "iMac",Fabricacao: 2023,Configuracao: {Processador: "Apple M1",Memoria: "16 Gb",Disco: "SSD 512Gb",Monitor: "Retina 24”",Teclado: "ABNT2",Mouse: "Magic Mouse"},Programas: ["macOS Monterey", "iWork Suite", "Sophos Antivirus"],Aquisicao: "17/05/2024",Valor: 3800.00}])
DeprecationWarning: Collection.insert() is deprecated. Use insertOne, insertMany, or bulkWrite.
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('66670c40e91f89cce86b8381') }
}
fred> db.computadores.insertMany([{Descricao: "Computador Apple iMac",Marca: "Apple",Modelo: "iMac",Fabricacao: 2023,Configuracao: {Processador: "Apple M1",Memoria: "16 Gb",Disco: "SSD 512Gb",Monitor: "Retina 24”",Teclado: "ABNT2",Mouse: "Magic Mouse"},Programas: ["macOS Monterey", "iWork Suite", "Sophos Antivirus"],Aquisicao: "17/05/2024",Valor: 3800.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('66670c67e91f89cce86b8382') }
}
fred> db.computadores.insertMany([{Descricao: "Computador Samsung Galaxy Book",Marca: "Samsung",Modelo: "Galaxy Book",Fabricacao: 2023,Configuracao: {Processador: "Intel Core i7",Memoria: "16 Gb",Disco: "SSD 1Tb",Monitor: "LED 15.6”",Teclado: "ABNT2",Mouse: "Touchpad"},Programas: ["Windows 11", "Microsoft 365", "Avast Antivirus"],Aquisicao: "25/05/2024",Valor: 3000.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('66670f98e91f89cce86b8383') }
}
fred> db.computadores.insertMany([{Descricao: "Computador Dell XPS",Marca: "Dell",Modelo: "XPS",Fabricacao: 2024,Configuracao: {Processador: "Intel Core i7",Memoria: "16 Gb",Disco: "SSD 512Gb",Monitor: "InfinityEdge 13.4” 4K",Teclado: "ABNT2",Mouse: "Óptico 2 Botões"},Programas: ["Windows 11", "Microsoft Office", "McAfee Antivirus"],Aquisicao: "12/05/2024",Valor: 3800.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('66671023e91f89cce86b8384') }
}
fred> db.computadores.find()
[
  {
    _id: ObjectId('6667092fe91f89cce86b837c'),
    Descricao: 'Computador Dell Inspiron',
    Marca: 'Dell',
    Modelo: 'Inspiron',
    Fabricacao: 2023,
    Configuracao: {
      Processador: 'Intel i5',
      Memoria: '8 Gb',
      Disco: 'HDD 500Gb',
      Monitor: 'LED 19”',
      Teclado: 'ABNT2',
      Mouse: 'Óptico 2 Botões'
    },
    Programas: [ 'Windows 10', 'Microsoft Office', 'Avast Antivirus' ],
    Aquisicao: '05/10/2024',
    Valor: 2500
  },
  {
    _id: ObjectId('66670a29e91f89cce86b837d'),
    Descricao: 'Computador HP Pavilion',
    Marca: 'HP',
    Modelo: 'Pavilion',
    Fabricacao: 2022,
    Configuracao: {
      Processador: 'AMD Ryzen 7',
      Memoria: '16 Gb',
      Disco: 'SSD 512Gb',
      Monitor: 'LED 24”',
      Teclado: 'ABNT2',
      Mouse: 'Óptico 3 Botões'
    },
    Programas: [ 'Windows 11', 'Office 365', 'McAfee Antivirus' ],
    Aquisicao: '15/05/2024',
    Valor: 3200
  },
  {
    _id: ObjectId('66670ad8e91f89cce86b837e'),
    Descricao: 'Computador Lenovo ThinkCentre',
    Marca: 'Lenovo',
    Modelo: 'ThinkCentre',
    Fabricacao: 2023,
    Configuracao: {
      Processador: 'Intel Core i3',
      Memoria: '4 Gb',
      Disco: 'HDD 1Tb',
      Monitor: 'LED 21.5”',
      Teclado: 'ABNT2',
      Mouse: 'Óptico 2 Botões'
    },
    Programas: [ 'Windows 10', 'LibreOffice', 'Avira Antivirus' ],
    Aquisicao: '20/05/2024',
    Valor: 1800
  },
  {
    _id: ObjectId('66670b50e91f89cce86b837f'),
    Descricao: 'Computador Acer Aspire',
    Marca: 'Acer',
    Modelo: 'Aspire',
    Fabricacao: 2024,
    Configuracao: {
      Processador: 'AMD Ryzen 5',
      Memoria: '12 Gb',
      Disco: 'SSD 256Gb',
      Monitor: 'LED 23.8”',
      Teclado: 'ABNT2',
      Mouse: 'Óptico 3 Botões'
    },
    Programas: [ 'Windows 11', 'Microsoft Office', 'Avast Antivirus' ],
    Aquisicao: '03/05/2024',
    Valor: 2800
  },
  {
    _id: ObjectId('66670bd3e91f89cce86b8380'),
    Descricao: 'Computador Asus ROG Strix',
    Marca: 'Asus',
    Modelo: 'ROG Strix',
    Fabricacao: 2023,
    Configuracao: {
      Processador: 'Intel Core i9',
      Memoria: '32 Gb',
      Disco: 'SSD 2Tb',
      Monitor: 'LED 27” 4K',
      Teclado: 'ABNT2',
      Mouse: 'Óptico 6 Botões'
    },
    Programas: [ 'Windows 11', 'Adobe Creative Suite', 'Norton Antivirus' ],
    Aquisicao: '08/05/2024',
    Valor: 5000
  },
  {
    _id: ObjectId('66670c40e91f89cce86b8381'),
    Descricao: 'Computador Apple iMac',
    Marca: 'Apple',
    Modelo: 'iMac',
    Fabricacao: 2023,
    Configuracao: {
      Processador: 'Apple M1',
      Memoria: '16 Gb',
      Disco: 'SSD 512Gb',
      Monitor: 'Retina 24”',
      Teclado: 'ABNT2',
      Mouse: 'Magic Mouse'
    },
    Programas: [ 'macOS Monterey', 'iWork Suite', 'Sophos Antivirus' ],
    Aquisicao: '17/05/2024',
    Valor: 3800
  },
  {
    _id: ObjectId('66670c67e91f89cce86b8382'),
    Descricao: 'Computador Apple iMac',
    Marca: 'Apple',
    Modelo: 'iMac',
    Fabricacao: 2023,
    Configuracao: {
      Processador: 'Apple M1',
      Memoria: '16 Gb',
      Disco: 'SSD 512Gb',
      Monitor: 'Retina 24”',
      Teclado: 'ABNT2',
      Mouse: 'Magic Mouse'
    },
    Programas: [ 'macOS Monterey', 'iWork Suite', 'Sophos Antivirus' ],
    Aquisicao: '17/05/2024',
    Valor: 3800
  },
  {
    _id: ObjectId('66670f98e91f89cce86b8383'),
    Descricao: 'Computador Samsung Galaxy Book',
    Marca: 'Samsung',
    Modelo: 'Galaxy Book',
    Fabricacao: 2023,
    Configuracao: {
      Processador: 'Intel Core i7',
      Memoria: '16 Gb',
      Disco: 'SSD 1Tb',
      Monitor: 'LED 15.6”',
      Teclado: 'ABNT2',
      Mouse: 'Touchpad'
    },
    Programas: [ 'Windows 11', 'Microsoft 365', 'Avast Antivirus' ],
    Aquisicao: '25/05/2024',
    Valor: 3000
  },
  {
    _id: ObjectId('66671023e91f89cce86b8384'),
    Descricao: 'Computador Dell XPS',
    Marca: 'Dell',
    Modelo: 'XPS',
    Fabricacao: 2024,
    Configuracao: {
      Processador: 'Intel Core i7',
      Memoria: '16 Gb',
      Disco: 'SSD 512Gb',
      Monitor: 'InfinityEdge 13.4” 4K',
      Teclado: 'ABNT2',
      Mouse: 'Óptico 2 Botões'
    },
    Programas: [ 'Windows 11', 'Microsoft Office', 'McAfee Antivirus' ],
    Aquisicao: '12/05/2024',
    Valor: 3800
  }
]
fred> db.computadores.insertMany([{Descricao: "Computador Lenovo IdeaCentre",Marca: "Lenovo", Modelo: "IdeaCentre",Fabricacao: 2024,Configuracao: {Processador: "AMD Ryzen 9",Memoria: "64 Gb",Disco: "SSD 4Tb",Monitor: "LED 32” 4K",Teclado: "ABNT2",Mouse: "Óptico 5 Botões"},Programas: ["Windows 11", "Microsoft Office", "Kaspersky Antivirus"],Aquisicao: "30/05/2024",Valor: 6000.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('666710d8e91f89cce86b8385') }
}
fred> db.computadores.insertMany([{Descricao: "Computador Microsoft Surface Studio",Marca: "Microsoft",Modelo: "Surface Studio",Fabricacao: 2023,Configuracao: {Processador: "Intel Core i7",Memoria: "32 Gb",Disco: "SSD 1Tb",Monitor: "PixelSense 28”",Teclado: "ABNT2",Mouse: "Surface Mouse"},Programas: ["Windows 11", "Microsoft Office", "Windows Defender"],Aquisicao: "28/05/2024",Valor: 4500.00}])
{
  acknowledged: true,
  insertedIds: { '0': ObjectId('66671143e91f89cce86b8386') }
}
fred> db.computadores.find()
[
  {
    _id: ObjectId('6667092fe91f89cce86b837c'),
    Descricao: 'Computador Dell Inspiron',
    Marca: 'Dell',
    Modelo: 'Inspiron',
    Fabricacao: 2023,
    Configuracao: {
      Processador: 'Intel i5',
      Memoria: '8 Gb',
      Disco: 'HDD 500Gb',
      Monitor: 'LED 19”',
      Teclado: 'ABNT2',
      Mouse: 'Óptico 2 Botões'
    },
    Programas: [ 'Windows 10', 'Microsoft Office', 'Avast Antivirus' ],
    Aquisicao: '05/10/2024',
    Valor: 2500
  },
  {
    _id: ObjectId('66670a29e91f89cce86b837d'),
    Descricao: 'Computador HP Pavilion',
    Marca: 'HP',
    Modelo: 'Pavilion',
    Fabricacao: 2022,
    Configuracao: {
      Processador: 'AMD Ryzen 7',
      Memoria: '16 Gb',
      Disco: 'SSD 512Gb',
      Monitor: 'LED 24”',
      Teclado: 'ABNT2',
      Mouse: 'Óptico 3 Botões'
    },
    Programas: [ 'Windows 11', 'Office 365', 'McAfee Antivirus' ],
    Aquisicao: '15/05/2024',
    Valor: 3200
  },
  {
    _id: ObjectId('66670ad8e91f89cce86b837e'),
    Descricao: 'Computador Lenovo ThinkCentre',
    Marca: 'Lenovo',
    Modelo: 'ThinkCentre',
    Fabricacao: 2023,
    Configuracao: {
      Processador: 'Intel Core i3',
      Memoria: '4 Gb',
      Disco: 'HDD 1Tb',
      Monitor: 'LED 21.5”',
      Teclado: 'ABNT2',
      Mouse: 'Óptico 2 Botões'
    },
    Programas: [ 'Windows 10', 'LibreOffice', 'Avira Antivirus' ],
    Aquisicao: '20/05/2024',
    Valor: 1800
  },
  {
    _id: ObjectId('66670b50e91f89cce86b837f'),
    Descricao: 'Computador Acer Aspire',
    Marca: 'Acer',
    Modelo: 'Aspire',
    Fabricacao: 2024,
    Configuracao: {
      Processador: 'AMD Ryzen 5',
      Memoria: '12 Gb',
      Disco: 'SSD 256Gb',
      Monitor: 'LED 23.8”',
      Teclado: 'ABNT2',
      Mouse: 'Óptico 3 Botões'
    },
    Programas: [ 'Windows 11', 'Microsoft Office', 'Avast Antivirus' ],
    Aquisicao: '03/05/2024',
    Valor: 2800
  },
  {
    _id: ObjectId('66670bd3e91f89cce86b8380'),
    Descricao: 'Computador Asus ROG Strix',
    Marca: 'Asus',
    Modelo: 'ROG Strix',
    Fabricacao: 2023,
    Configuracao: {
      Processador: 'Intel Core i9',
      Memoria: '32 Gb',
      Disco: 'SSD 2Tb',
      Monitor: 'LED 27” 4K',
      Teclado: 'ABNT2',
      Mouse: 'Óptico 6 Botões'
    },
    Programas: [ 'Windows 11', 'Adobe Creative Suite', 'Norton Antivirus' ],
    Aquisicao: '08/05/2024',
    Valor: 5000
  },
  {
    _id: ObjectId('66670c40e91f89cce86b8381'),
    Descricao: 'Computador Apple iMac',
    Marca: 'Apple',
    Modelo: 'iMac',
    Fabricacao: 2023,
    Configuracao: {
      Processador: 'Apple M1',
      Memoria: '16 Gb',
      Disco: 'SSD 512Gb',
      Monitor: 'Retina 24”',
      Teclado: 'ABNT2',
      Mouse: 'Magic Mouse'
    },
    Programas: [ 'macOS Monterey', 'iWork Suite', 'Sophos Antivirus' ],
    Aquisicao: '17/05/2024',
    Valor: 3800
  },
  {
    _id: ObjectId('66670c67e91f89cce86b8382'),
    Descricao: 'Computador Apple iMac',
    Marca: 'Apple',
    Modelo: 'iMac',
    Fabricacao: 2023,
    Configuracao: {
      Processador: 'Apple M1',
      Memoria: '16 Gb',
      Disco: 'SSD 512Gb',
      Monitor: 'Retina 24”',
      Teclado: 'ABNT2',
      Mouse: 'Magic Mouse'
    },
    Programas: [ 'macOS Monterey', 'iWork Suite', 'Sophos Antivirus' ],
    Aquisicao: '17/05/2024',
    Valor: 3800
  },
  {
    _id: ObjectId('66670f98e91f89cce86b8383'),
    Descricao: 'Computador Samsung Galaxy Book',
    Marca: 'Samsung',
    Modelo: 'Galaxy Book',
    Fabricacao: 2023,
    Configuracao: {
      Processador: 'Intel Core i7',
      Memoria: '16 Gb',
      Disco: 'SSD 1Tb',
      Monitor: 'LED 15.6”',
      Teclado: 'ABNT2',
      Mouse: 'Touchpad'
    },
    Programas: [ 'Windows 11', 'Microsoft 365', 'Avast Antivirus' ],
    Aquisicao: '25/05/2024',
    Valor: 3000
  },
  {
    _id: ObjectId('66671023e91f89cce86b8384'),
    Descricao: 'Computador Dell XPS',
    Marca: 'Dell',
    Modelo: 'XPS',
    Fabricacao: 2024,
    Configuracao: {
      Processador: 'Intel Core i7',
      Memoria: '16 Gb',
      Disco: 'SSD 512Gb',
      Monitor: 'InfinityEdge 13.4” 4K',
      Teclado: 'ABNT2',
      Mouse: 'Óptico 2 Botões'
    },
    Programas: [ 'Windows 11', 'Microsoft Office', 'McAfee Antivirus' ],
    Aquisicao: '12/05/2024',
    Valor: 3800
  },
  {
    _id: ObjectId('666710d8e91f89cce86b8385'),
    Descricao: 'Computador Lenovo IdeaCentre',
    Marca: 'Lenovo',
    Modelo: 'IdeaCentre',
    Fabricacao: 2024,
    Configuracao: {
      Processador: 'AMD Ryzen 9',
      Memoria: '64 Gb',
      Disco: 'SSD 4Tb',
      Monitor: 'LED 32” 4K',
      Teclado: 'ABNT2',
      Mouse: 'Óptico 5 Botões'
    },
    Programas: [ 'Windows 11', 'Microsoft Office', 'Kaspersky Antivirus' ],
    Aquisicao: '30/05/2024',
    Valor: 6000
  },
  {
    _id: ObjectId('66671143e91f89cce86b8386'),
    Descricao: 'Computador Microsoft Surface Studio',
    Marca: 'Microsoft',
    Modelo: 'Surface Studio',
    Fabricacao: 2023,
    Configuracao: {
      Processador: 'Intel Core i7',
      Memoria: '32 Gb',
      Disco: 'SSD 1Tb',
      Monitor: 'PixelSense 28”',
      Teclado: 'ABNT2',
      Mouse: 'Surface Mouse'
    },
    Programas: [ 'Windows 11', 'Microsoft Office', 'Windows Defender' ],
    Aquisicao: '28/05/2024',
    Valor: 4500
  }
]
fred>
