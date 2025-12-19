<script lang="ts">
    const testimonials = [
        {
            name: "Anna",
            age: 32,
            text: "Dzięki metodzie Roetzera i wsparciu Natalii w końcu rozumiem swoje ciało. Po latach stosowania pigułki, odkryłam naturalny rytm mojego cyklu. To niesamowite uczucie wolności!",
            image: "/generated/image-happy-woman-in-her-late-20s-smiling-natu-1766181333870-5.webp"
        },
        {
            name: "Kasia",
            age: 28,
            text: "Metoda Creightona pomogła nam z mężem świadomie planować rodzinę. Natalia jest cierpliwa, kompetentna i zawsze dostępna, gdy mam pytania. Polecam każdej kobiecie!",
            image: "/generated/image-happy-woman-in-her-late-20s-smiling-natu-1766181333870-5.webp"
        },
        {
            name: "Monika",
            age: 35,
            text: "Aromaterapia w połączeniu z NPR to prawdziwa rewolucja. Olejki pomogły mi złagodzić bolesne miesiączki i PMS. Czuję się bardziej zrównoważona i w zgodzie ze sobą.",
            image: "/generated/image-happy-woman-in-her-late-20s-smiling-natu-1766181333870-5.webp"
        }
    ];
</script>

<section class="bg-gray-50 py-24">
    <div class="container mx-auto px-6 md:px-12 text-center">
        <h2 class="text-4xl md:text-[44px] leading-tight font-light tracking-tight mb-4 text-gray-900">
            Historie moich klientek
        </h2>
        <p class="text-[15px] text-gray-600 font-light mb-16 tracking-wide max-w-2xl mx-auto">
            Poznaj doświadczenia kobiet, które odkryły siłę naturalnego planowania rodziny i holistycznego podejścia do zdrowia.
        </p>

        <!-- Testimonials Grid -->
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-6xl mx-auto">
            {#each testimonials as testimonial}
                <div class="bg-white rounded-2xl p-8 shadow-lg hover:shadow-xl transition-shadow text-left">
                    <div class="flex items-center gap-4 mb-6">
                        <div class="w-16 h-16 rounded-full bg-primary-100 flex items-center justify-center text-2xl">
                            👤
                        </div>
                        <div>
                            <h3 class="font-medium text-gray-900">{testimonial.name}</h3>
                            <p class="text-sm text-gray-500">{testimonial.age} lat</p>
                        </div>
                    </div>
                    <p class="text-gray-700 leading-relaxed text-[15px] font-light italic">
                        "{testimonial.text}"
                    </p>
                </div>
            {/each}
        </div>

        <!-- Bottom Note -->
        <div class="mt-16 max-w-2xl mx-auto">
            <p class="text-sm text-gray-500 italic">
                Imiona zostały zmienione w celu ochrony prywatności klientek.
            </p>
        </div>
    </div>
</section>
