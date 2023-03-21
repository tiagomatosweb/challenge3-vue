<template>
    <div class="m-10 px-4 sm:px-6 lg:px-8">
        <h1 class="text-lg font-semibold leading-6 text-gray-900">Usuários</h1>

        <div class="mt-8 flow-root">
            <div class="-my-2 -mx-4 overflow-x-auto sm:-mx-6 lg:-mx-8">
                <div class="inline-block min-w-full py-2 align-middle sm:px-6 lg:px-8">
                    <div class="relative">
                         <div class="absolute top-0 left-14 flex h-12 items-center space-x-3 bg-white sm:left-12">
                           <button type="button" class="inline-flex items-center rounded bg-white px-2 py-1 text-sm font-semibold text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 hover:bg-gray-50 disabled:cursor-not-allowed disabled:opacity-30 disabled:hover:bg-white">Deletar todos</button>
                         </div>

                        <table class="min-w-full table-fixed divide-y divide-gray-300">
                            <thead>
                            <tr>
                                <th scope="col" class="relative px-7 sm:w-12 sm:px-6">
                                    <input type="checkbox" class="absolute left-4 top-1/2 -mt-2 h-4 w-4 rounded border-gray-300 text-indigo-600 focus:ring-indigo-600">
                                </th>
                                <th scope="col" class="min-w-[12rem] py-3.5 pr-3 text-left text-sm font-semibold text-gray-900">Nome</th>
                                <th scope="col" class="px-3 py-3.5 text-left text-sm font-semibold text-gray-900">Email</th>
                                <th scope="col" class="px-3 py-3.5 text-left text-sm font-semibold text-gray-900">Cargo</th>
                            </tr>
                            </thead>
                            <tbody class="divide-y divide-gray-200 bg-white">
                            <tr>
                                <td class="relative px-7 sm:w-12 sm:px-6">
                                    <input type="checkbox" class="absolute left-4 top-1/2 -mt-2 h-4 w-4 rounded border-gray-300 text-indigo-600 focus:ring-indigo-600">
                                </td>
                                <td class="whitespace-nowrap py-4 pr-3 text-sm font-medium text-gray-900">Leanne Graham</td>
                                <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-500">Sincere@april.biz</td>
                                <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-500">Membro</td>
                            </tr>
                            <tr>
                                <td class="relative px-7 sm:w-12 sm:px-6">
                                    <input type="checkbox" class="absolute left-4 top-1/2 -mt-2 h-4 w-4 rounded border-gray-300 text-indigo-600 focus:ring-indigo-600">
                                </td>
                                <td class="whitespace-nowrap py-4 pr-3 text-sm font-medium text-gray-900">Leanne Graham</td>
                                <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-500">Sincere@april.biz</td>
                                <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-500">Membro</td>
                            </tr>
                            <tr>
                                <td class="relative px-7 sm:w-12 sm:px-6">
                                    <input type="checkbox" class="absolute left-4 top-1/2 -mt-2 h-4 w-4 rounded border-gray-300 text-indigo-600 focus:ring-indigo-600">
                                </td>
                                <td class="whitespace-nowrap py-4 pr-3 text-sm font-medium text-gray-900">Leanne Graham</td>
                                <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-500">Sincere@april.biz</td>
                                <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-500">Membro</td>
                            </tr>
                            </tbody>
                        </table>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
import { ref } from 'vue';

const users = ref([
    {
        "id": 1,
        "name": "Leanne Graham",
        "email": "Sincere@april.biz",
        "cargo": "Membro",
    },
    {
        "id": 2,
        "name": "Ervin Howell",
        "email": "Shanna@melissa.tv",
        "cargo": "Membro",
    },
    {
        "id": 3,
        "name": "Clementine Bauch",
        "email": "Nathan@yesenia.net",
        "cargo": "Admin",
    },
    {
        "id": 4,
        "name": "Patricia Lebsack",
        "email": "Julianne.OConner@kory.org",
        "cargo": "Membro",
    },
    {
        "id": 5,
        "name": "Chelsey Dietrich",
        "email": "Lucio_Hettinger@annie.ca",
        "cargo": "Membro",
    },
    {
        "id": 6,
        "name": "Mrs. Dennis Schulist",
        "email": "Karley_Dach@jasper.info",
        "cargo": "Membro",
    },
    {
        "id": 7,
        "name": "Kurtis Weissnat",
        "email": "Telly.Hoeger@billy.biz",
        "cargo": "Gerente",
    },
    {
        "id": 8,
        "name": "Nicholas Runolfsdottir V",
        "email": "Sherwood@rosamond.me",
        "cargo": "Membro",
    },
    {
        "id": 9,
        "name": "Glenna Reichert",
        "email": "Chaim_McDermott@dana.io",
        "cargo": "Membro",
    },
    {
        "id": 10,
        "name": "Clementina DuBuque",
        "email": "Rey.Padberg@karina.biz",
        "cargo": "Membro",
    }
])
</script>
