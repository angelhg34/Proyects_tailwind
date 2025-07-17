Ejemplo de sintaxis para aplicar grid:
<body class=" h-screen bg-linear-to-r from-cyan-500 to-blue-900 text-white grid grid-cols-3"> 
    <div class=" row-span-2 bg-amber-400">1</div>
    <div class=" bg-blue-400">2</div>
    <div class=" bg-red-400">3</div>
    <div class=" bg-green-300">4</div>
    <div class=" bg-cyan-800">5</div>
    <div class=" bg-amber-100">6</div>

Ejemplo de textos, anchos, altos, etc:
<section class="w-[200px] h-[200px] m-[20px] bg-amber-50 flex ">
        <span cl>Bloque 1</span>
        <span>Bloque 2</span>
        <h1 class="text-4xl text-center font-[Times_New_Roman]">Hello world, learning tailwind css</h1>
    </section>


Ejemplo de grupos y subgrupos:
    <section class="p-4 bg-gray-100 hover:bg-gray-300 rounded-md h-20 group">
        <button class="bg-amber-600 p-2  group-hover:bg-red-500">Enviar</button>
    </section>
    <div class="group/card p-6 bg-gray-200 rounded-lg hover:bg-gray-300">
        <h2 class="text-xl font-bold">Card Principal</h2>
        <button class="mt-4 px-4 bg-blue-500 text-white group-hover/card:bg-red-500">Botón Principal</button>
        <div class="group/subcard p-4 m-4 bg-white rounded-md hover:bg-gray-100">
            <h3 class="text-lg font-semibold">Card secundaria</h3>
            <button class="mt-2 py-2 bg-green-500 text-white group-hover/subcard:bg-purple-500">Botón secundario</button>
        </div>
        
    </div>