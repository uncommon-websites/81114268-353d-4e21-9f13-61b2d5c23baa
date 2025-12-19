<script lang="ts">
    const services = [
        {
            title: "Metoda Roetzera",
            description: "Kompleksowa nauka obserwacji cyklu płodności metodą objawowo-termiczną",
            image: "/generated/image-womans-hands-writing-in-a-fertility-trac-1766181326291-2.webp",
            icon: "📊"
        },
        {
            title: "Model Creightona",
            description: "Certyfikowana instrukcja FertilityCare™ w systemie NaProTechnology",
            image: "/generated/image-womans-hands-writing-in-a-fertility-trac-1766181326291-2.webp",
            icon: "📝"
        },
        {
            title: "Aromaterapia",
            description: "Wsparcie olejkami eterycznymi dla zdrowia kobiecego i równowagi hormonalnej",
            image: "/generated/image-essential-oil-bottles-arranged-beautiful-1766181331212-4.webp",
            icon: "🌿"
        },
        {
            title: "Warsztaty dla Mam i Córek",
            description: "Rozmowy o dojrzewaniu, cyklu i kobiecości w bezpiecznej atmosferze",
            image: "/generated/image-mother-and-teenage-daughter-sitting-toge-1766181328783-3.webp",
            icon: "💝"
        }
    ];
</script>

<section id="services" class="bg-gray-900 py-24">
    <div class="container mx-auto px-6 md:px-12">
        <div class="flex flex-col md:flex-row justify-between items-end mb-16 text-white">
            <div class="max-w-2xl">
                <h2 class="text-4xl md:text-[44px] leading-tight font-light tracking-tight mb-6">Holistyczne podejście do zdrowia kobiecego</h2>
                <p class="text-[17px] text-white/80 font-light max-w-md leading-relaxed">Łączę certyfikowane metody naturalnego planowania rodziny z aromaterapią, by wspierać Cię w świadomym poznawaniu swojego ciała.</p>
            </div>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
            {#each services as service}
                <div class="group relative flex flex-col p-8 rounded-lg bg-gray-800 hover:bg-gray-750 transition-all duration-300 hover:transform hover:-translate-y-1 h-full border border-gray-700/50">
                    <div class="text-4xl mb-4">{service.icon}</div>
                    <h3 class="text-white text-xl font-medium mb-4 leading-tight">{service.title}</h3>
                    <p class="text-white/70 text-sm leading-relaxed mb-6 flex-grow">{service.description}</p>
                    <div class="mt-auto">
                        <a href="#consultation" class="inline-flex items-center text-[13px] font-medium text-primary-300 hover:text-primary-200 transition-colors">
                            Dowiedz się więcej <span class="ml-2">→</span>
                        </a>
                    </div>
                </div>
            {/each}
        </div>
    </div>
</section>
