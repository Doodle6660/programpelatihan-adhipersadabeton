<template>
    <main class="h-full overflow-y-auto">
        <div
            class="container px-6 mx-auto grid animate__animated animate__fadeInUpBig animate__slow"
        >
            <h2 class="my-6 text-2xl font-semibold text-gray-700 uppercase">
                DASHBOARD SUMMARY PELAKSANAAN PELATIHAN | SDM
            </h2>

            <div class="flex flex-wrap gap-3 mb-5">
                <input
                    type="date"
                    class="flex items-center justify-between w-28 md:w-44 px-4 py-3 bg-white shadow-md text-sm font-medium leading-5 transition-colors duration-150 border border-transparent rounded-lg focus:outline-none focus:shadow-outline-red"
                />
                <input
                    type="date"
                    class="flex items-center justify-between w-28 md:w-44 px-4 py-3 bg-white shadow-md text-sm font-medium leading-5 transition-colors duration-150 border border-transparent rounded-lg focus:outline-none focus:shadow-outline-red"
                />
                <div class="flex items-center justify-between">
                    <button
                        class="flex items-center justify-between px-2 py-2 text-sm font-medium leading-5 text-white transition-colors duration-150 bg-red-600 border border-transparent rounded-lg active:bg-red-600 hover:bg-red-700 focus:outline-none focus:shadow-outline-red"
                    >
                        <svg
                            xmlns="http://www.w3.org/2000/svg"
                            class="w-5 h-5"
                            viewBox="0 0 24 24"
                            fill="none"
                            stroke="currentColor"
                            stroke-width="2"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                        >
                            <circle cx="11" cy="11" r="8"></circle>
                            <line x1="21" y1="21" x2="16.65" y2="16.65"></line>
                        </svg>
                    </button>
                </div>
            </div>

            <!-- Cards -->
            <div class="grid gap-6 mb-8 md:grid-cols-2 xl:grid-cols-4">
                <!-- Card -->
                <div
                    class="flex items-center p-4 bg-white rounded-lg shadow-xs border-solid border-2 border-orange-400 transform transition duration-500 hover:scale-110"
                >
                    <div>
                        <p class="mb-2 text-sm font-medium text-orange-500">
                            Pelatihan Soft Skill
                        </p>
                        <p class="text-lg font-semibold text-gray-700">
                            0 Pelatihan
                        </p>
                    </div>
                </div>
                <!-- Card -->
                <div
                    class="flex items-center p-4 bg-white rounded-lg shadow-xs border-solid border-2 border-blue-400 transform transition duration-500 hover:scale-110"
                >
                    <div>
                        <p class="mb-2 text-sm font-medium text-blue-500">
                            Pelatihan Teknik
                        </p>
                        <p class="text-lg font-semibold text-gray-700">
                            0 Pelatihan
                        </p>
                    </div>
                </div>
                <!-- Card -->
                <div
                    class="flex items-center p-4 bg-white rounded-lg shadow-xs border-solid border-2 border-green-400  transform transition duration-500 hover:scale-110"
                >
                    <div>
                        <p class="mb-2 text-sm font-medium text-green-500">
                            Pelatihan Non Teknik
                        </p>
                        <p class="text-lg font-semibold text-gray-700">
                            0 Pelatihan
                        </p>
                    </div>
                </div>
                <!-- Card -->
                <div
                    class="flex items-center p-4 bg-white rounded-lg shadow-xs border-solid border-2 border-purple-500 transform transition duration-500 hover:scale-110"
                >
                    <div>
                        <p class="mb-2 text-sm font-medium text-purple-600">
                            Pelatihan General Skill
                        </p>
                        <p class="text-lg font-semibold text-gray-700">
                            0 Pelatihan
                        </p>
                    </div>
                </div>
            </div>

            <div class="grid gap-6 mb-8 md:grid-cols-2 xl:grid-cols-6">
                <!-- Card -->
                <div
                    class="flex items-center p-4 rounded-lg shadow-xs bg-green-400 col-span-2"
                >
                    <div>
                        <p class="mb-2 text-sm font-medium text-white">
                            ANGGARAN PELATIHAN YANG DIRENCANAKAN
                        </p>

                        <p class="text-xl font-semibold text-green-800">
                            Rp. 000,000,000
                        </p>
                    </div>
                </div>
                <div
                    class="flex items-center p-4 rounded-lg shadow-xs bg-indigo-500 col-span-2"
                >
                    <div>
                        <p class="mb-2 text-sm font-medium text-white">
                            TOTAL ANGGARAN PELATIHAN YANG TEREALISASI
                        </p>

                        <p class="text-xl font-semibold text-indigo-900">
                            Rp. 000,000,000
                        </p>
                    </div>
                </div>
                <div
                    class="flex items-center p-4 rounded-lg shadow-xs bg-blue-500 col-span-2"
                >
                    <div>
                        <p class="mb-2 text-sm font-medium text-white">
                            SISA ANGGARAN PELATIHAN
                        </p>

                        <p class="text-xl font-semibold text-blue-900">
                            Rp. 000,000,000
                        </p>
                    </div>
                </div>
            </div>

            <!-- New Table -->
            <div class="w-full overflow-hidden rounded-lg shadow-xs">
                <div class="w-full overflow-x-auto">
                    <table class="w-full whitespace-no-wrap">
                        <thead>
                            <tr
                                class="text-xs font-semibold tracking-wide text-left text-gray-500 uppercase border-b bg-gray-50"
                            >
                                <th class="px-4 py-3 text-center">
                                    #
                                </th>
                                <th class="px-4 py-3 text-center">
                                    Nama
                                </th>
                                <th class="px-4 py-3 text-center">
                                    NPP
                                </th>
                                <th class="px-4 py-3 text-center">
                                    Unit Kerja
                                </th>
                                <th class="px-4 py-3 text-center">
                                    Jabatan
                                </th>
                                <th class="px-4 py-3 text-center">
                                    Penugasan Saat Ini
                                </th>
                                <th class="px-4 py-3 text-center">
                                    Bidang
                                </th>
                                <th class="px-4 py-3 text-center">
                                    Nama Pelatihan
                                </th>
                                <th class="px-4 py-3 text-center">
                                    Waktu Pelaksanaan Pelatihan
                                </th>
                                <th class="px-4 py-3 text-center">
                                    Lokasi Pelaksanaan
                                </th>
                                <th class="px-4 py-3 text-center">
                                    Biaya Pelatihan
                                </th>
                                <th class="px-4 py-3 text-center">
                                    Status Pelaksanaan
                                </th>
                                <th class="px-4 py-3 text-center">
                                    Total Score
                                </th>
                                <th class="px-4 py-3 text-center">
                                    Keterangan
                                </th>
                            </tr>
                        </thead>
                        <tbody class="bg-white divide-y">
                            <tr
                                v-for="pel in pelatihan"
                                :key="pel.no"
                                class="text-gray-700"
                            >
                                <td :class="dataclass">
                                    <span
                                        class="font-semibold w-full h-full text-center"
                                    >
                                        {{ pel.no }}
                                    </span>
                                </td>
                                <td :class="dataclass">
                                    {{ pel.nama }}
                                </td>
                                <td :class="dataclass">
                                    {{ pel.npp }}
                                </td>
                                <td :class="dataclass">
                                    {{ pel.unit }}
                                </td>
                                <td :class="dataclass">
                                    <span class="font-semibold text-red-500">
                                        {{ pel.jabatan }}
                                    </span>
                                </td>
                                <td :class="dataclass">
                                    {{ pel.penugasan }}
                                </td>
                                <td :class="dataclass">
                                    {{ pel.bidang }}
                                </td>
                                <td :class="dataclass">
                                    {{ pel.namapelatihan }}
                                </td>
                                <td :class="dataclass">
                                    <span class="font-semibold text-orange-500">
                                        {{ pel.waktu }}
                                    </span>
                                </td>
                                <td :class="dataclass">
                                    {{ pel.lokasi }}
                                </td>
                                <td :class="dataclass">
                                    <span class="font-semibold text-blue-500">
                                        {{ pel.biaya }}
                                    </span>
                                </td>
                                <td :class="dataclass">
                                    <span
                                        :class="{
                                            true: pel.isTrue,
                                            false: !pel.isTrue,
                                        }"
                                    >
                                        {{ pel.status }}
                                    </span>
                                </td>
                                <td :class="dataclass">
                                    {{ pel.score }}
                                </td>
                                <td :class="dataclass">
                                    {{ pel.keterangan }}
                                </td>
                            </tr>
                        </tbody>
                    </table>
                </div>
                <div
                    class="grid px-4 py-3 text-xs font-semibold tracking-wide text-gray-500 uppercase border-t bg-gray-50 sm:grid-cols-9"
                >
                    <span class="flex items-center col-span-3">
                        Showing 1-10 of 100
                    </span>
                    <span class="col-span-2"></span>
                    <!-- Pagination -->
                    <span
                        class="flex col-span-4 mt-2 sm:mt-auto sm:justify-end"
                    >
                        <nav aria-label="Table navigation">
                            <ul class="inline-flex items-center">
                                <li>
                                    <button
                                        class="px-3 py-1 rounded-md rounded-l-lg focus:outline-none focus:shadow-outline-red"
                                        aria-label="Previous"
                                    >
                                        <svg
                                            aria-hidden="true"
                                            class="w-4 h-4 fill-current"
                                            viewBox="0 0 20 20"
                                        >
                                            <path
                                                d="M12.707 5.293a1 1 0 010 1.414L9.414 10l3.293 3.293a1 1 0 01-1.414 1.414l-4-4a1 1 0 010-1.414l4-4a1 1 0 011.414 0z"
                                                clip-rule="evenodd"
                                                fill-rule="evenodd"
                                            ></path>
                                        </svg>
                                    </button>
                                </li>
                                <li>
                                    <button
                                        class="px-3 py-1 text-white transition-colors duration-150 bg-red-600 border border-r-0 border-red-600 rounded-md focus:outline-none focus:shadow-outline-red"
                                    >
                                        1
                                    </button>
                                </li>
                                <li>
                                    <button
                                        class="px-3 py-1 rounded-md focus:outline-none focus:shadow-outline-red"
                                    >
                                        2
                                    </button>
                                </li>
                                <li>
                                    <button
                                        class="px-3 py-1 rounded-md focus:outline-none focus:shadow-outline-red"
                                    >
                                        3
                                    </button>
                                </li>
                                <li>
                                    <button
                                        class="px-3 py-1 rounded-md focus:outline-none focus:shadow-outline-red"
                                    >
                                        4
                                    </button>
                                </li>
                                <li>
                                    <span class="px-3 py-1">...</span>
                                </li>
                                <li>
                                    <button
                                        class="px-3 py-1 rounded-md focus:outline-none focus:shadow-outline-red"
                                    >
                                        8
                                    </button>
                                </li>
                                <li>
                                    <button
                                        class="px-3 py-1 rounded-md focus:outline-none focus:shadow-outline-red"
                                    >
                                        9
                                    </button>
                                </li>
                                <li>
                                    <button
                                        class="px-3 py-1 rounded-md rounded-r-lg focus:outline-none focus:shadow-outline-red"
                                        aria-label="Next"
                                    >
                                        <svg
                                            class="w-4 h-4 fill-current"
                                            aria-hidden="true"
                                            viewBox="0 0 20 20"
                                        >
                                            <path
                                                d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z"
                                                clip-rule="evenodd"
                                                fill-rule="evenodd"
                                            ></path>
                                        </svg>
                                    </button>
                                </li>
                            </ul>
                        </nav>
                    </span>
                </div>
            </div>
        </div>
    </main>
</template>

<script>
export default {
    data() {
        return {
            dataclass: "px-4 py-3 text-sm text-center",
            pelatihan: [
                {
                    no: "1",
                    nama: "Applestore Tester",
                    npp: "applestore",
                    unit: "Bagian Test",
                    jabatan: "Staff Test",
                    penugasan: "Kantor Test",
                    bidang: "Bidang Test",
                    namapelatihan: "Testing nama pelatihan 1",
                    waktu: "14/10/2020",
                    lokasi: "Lokasi Test",
                    biaya: "5.000.000",
                    status: "true",
                    score: "n/a",
                    keterangan: "n/a",
                    isTrue: true,
                },
                {
                    no: "2",
                    nama: "Androidstore Tester",
                    npp: "androidstore",
                    unit: "Bagian Test",
                    jabatan: "Staff Test",
                    penugasan: "Kantor Test",
                    bidang: "Bidang Test",
                    namapelatihan: "Testing nama pelatihan 2",
                    waktu: "14/10/2020",
                    lokasi: "Lokasi Test",
                    biaya: "5.000.000",
                    status: "false",
                    score: "n/a",
                    keterangan: "n/a",
                    isTrue: false,
                },
            ],
        }
    },
}
</script>

<style scoped>
td > span.true {
    @apply px-2;
    @apply py-1;
    @apply font-semibold;
    @apply leading-tight;
    @apply text-green-700;
    @apply bg-green-100;
    @apply rounded-full;
}

td > span.false {
    @apply px-2;
    @apply py-1;
    @apply font-semibold;
    @apply leading-tight;
    @apply text-red-700;
    @apply bg-red-100;
    @apply rounded-full;
}
</style>
