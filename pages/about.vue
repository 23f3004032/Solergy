<template>
  <div class="min-h-screen bg-gray-50">
    <!-- Hero Carousel -->
    <HeroCarousel />

    <!-- Director Profile -->
    <section class="section bg-white">
      <div class="container-custom">
        <div class="max-w-4xl mx-auto">
          <div class="text-center mb-12">
            <h2 class="text-3xl font-bold text-gray-900 mb-4">Message from Our Director</h2>
            <div class="w-24 h-1 bg-primary mx-auto"></div>
          </div>
          
          <div class="bg-gradient-to-br from-gray-50 to-blue-50 rounded-2xl shadow-lg p-8 lg:p-12">
            <div class="flex flex-col lg:flex-row gap-8 items-center lg:items-start">
              <div class="flex-shrink-0">
                <div class="w-32 h-32 bg-gradient-to-br from-primary to-blue-600 rounded-full flex items-center justify-center text-white text-5xl font-bold shadow-xl">
                  SS
                </div>
              </div>
              <div class="flex-1">
                <h3 class="text-2xl font-bold text-gray-900 mb-2">Shubham Singh</h3>
                <p class="text-primary font-semibold mb-6">Director, Solergy Systems</p>
                <div class="space-y-4 text-gray-700 italic border-l-4 border-primary pl-6">
                  <p>
                    "At Solergy Systems, we believe that sustainable energy is not just the future—it's the present. 
                    Our mission is to empower every home and business in Bihar with clean, reliable, and affordable 
                    solar energy solutions."
                  </p>
                  <p>
                    "We've built our reputation on three core principles: quality, integrity, and customer-first service. 
                    Every project we undertake is a step toward a greener Bihar and a sustainable planet for future generations."
                  </p>
                  <p>
                    "Thank you for trusting us with your energy needs. Together, we're not just installing solar panels—we're 
                    building a brighter, cleaner tomorrow."
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Location & Contact -->
    <section class="section">
      <div class="container-custom">
        <div class="text-center mb-12">
          <h2 class="text-3xl font-bold text-gray-900 mb-4">Visit Our Office</h2>
          <p class="text-xl text-gray-600">We'd love to discuss your solar energy needs in person</p>
        </div>

        <div class="grid lg:grid-cols-2 gap-8">
          <!-- Contact Information -->
          <div class="glass-card p-8 relative overflow-hidden group rounded-3xl bg-gradient-to-br from-primary/10 via-blue-500/5 to-purple-500/10 hover:from-primary/20 hover:via-blue-500/15 hover:to-purple-500/20 transition-all duration-500 hover:shadow-2xl hover:shadow-primary/20">
            <div class="absolute inset-0 bg-gradient-to-br from-primary/10 to-blue-500/10 opacity-0 group-hover:opacity-100 transition-opacity duration-500 blur-xl"></div>
            <div class="relative z-10">
              <h3 class="text-2xl font-bold text-gray-900 mb-8">Contact Information</h3>
              
              <div class="space-y-6">
                <div class="flex items-start gap-4 group/item hover:translate-x-2 transition-transform duration-300">
                  <div class="w-14 h-14 bg-gradient-to-br from-primary to-blue-600 rounded-xl flex items-center justify-center flex-shrink-0 shadow-lg shadow-primary/30">
                    <svg class="w-7 h-7 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                    </svg>
                  </div>
                  <div>
                    <h4 class="font-bold text-lg text-gray-900 mb-2">Office Address</h4>
                    <p class="text-gray-600 leading-relaxed">
                      Bazar Samiti Road, Near Mahila Thana<br>
                      Infront of Tathagat Gas Agency<br>
                      Hajipur, Bihar - 844101
                    </p>
                  </div>
                </div>

                <div class="flex items-start gap-4 group/item hover:translate-x-2 transition-transform duration-300">
                  <div class="w-14 h-14 bg-gradient-to-br from-green to-green-600 rounded-xl flex items-center justify-center flex-shrink-0 shadow-lg shadow-green/30">
                    <svg class="w-7 h-7 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
                    </svg>
                  </div>
                  <div>
                    <h4 class="font-bold text-lg text-gray-900 mb-2">Phone</h4>
                    <a href="tel:+919973953809" class="text-primary hover:text-blue-600 transition-colors text-lg font-semibold">
                      +91 99739 53809
                    </a>
                  </div>
                </div>

                <div class="flex items-start gap-4 group/item hover:translate-x-2 transition-transform duration-300">
                  <div class="w-14 h-14 bg-gradient-to-br from-orange to-orange-600 rounded-xl flex items-center justify-center flex-shrink-0 shadow-lg shadow-orange/30">
                    <svg class="w-7 h-7 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                    </svg>
                  </div>
                  <div>
                    <h4 class="font-bold text-lg text-gray-900 mb-2">Email</h4>
                    <a href="mailto:solergysystems7@gmail.com" class="text-primary hover:text-blue-600 transition-colors font-semibold break-all">
                      solergysystems7@gmail.com
                    </a>
                  </div>
                </div>
              </div>

              <div class="mt-8 pt-8 border-t border-gray-200/50">
                <h4 class="font-bold text-lg text-gray-900 mb-4">Connect With Us</h4>
                <div class="flex gap-4">
                  <a href="#" class="w-14 h-14 bg-gradient-to-br from-blue-600 to-blue-700 hover:from-blue-700 hover:to-blue-800 text-white rounded-xl flex items-center justify-center transition-all duration-300 transform hover:scale-110 shadow-lg hover:shadow-blue-600/50" aria-label="Facebook">
                    <svg class="w-7 h-7" fill="currentColor" viewBox="0 0 24 24"><path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/></svg>
                  </a>
                  <a href="#" class="w-14 h-14 bg-gradient-to-br from-red-600 to-red-700 hover:from-red-700 hover:to-red-800 text-white rounded-xl flex items-center justify-center transition-all duration-300 transform hover:scale-110 shadow-lg hover:shadow-red-600/50" aria-label="YouTube">
                    <svg class="w-7 h-7" fill="currentColor" viewBox="0 0 24 24"><path d="M23.498 6.186a3.016 3.016 0 0 0-2.122-2.136C19.505 3.545 12 3.545 12 3.545s-7.505 0-9.377.505A3.017 3.017 0 0 0 .502 6.186C0 8.07 0 12 0 12s0 3.93.502 5.814a3.016 3.016 0 0 0 2.122 2.136c1.871.505 9.376.505 9.376.505s7.505 0 9.377-.505a3.015 3.015 0 0 0 2.122-2.136C24 15.93 24 12 24 12s0-3.93-.502-5.814zM9.545 15.568V8.432L15.818 12l-6.273 3.568z"/></svg>
                  </a>
                  <a href="#" class="w-14 h-14 bg-gradient-to-br from-pink-600 to-pink-700 hover:from-pink-700 hover:to-pink-800 text-white rounded-xl flex items-center justify-center transition-all duration-300 transform hover:scale-110 shadow-lg hover:shadow-pink-600/50" aria-label="Instagram">
                    <svg class="w-7 h-7" fill="currentColor" viewBox="0 0 24 24"><path d="M12 0C8.74 0 8.333.015 7.053.072 5.775.132 4.905.333 4.14.63c-.789.306-1.459.717-2.126 1.384S.935 3.35.63 4.14C.333 4.905.131 5.775.072 7.053.012 8.333 0 8.74 0 12s.015 3.667.072 4.947c.06 1.277.261 2.148.558 2.913.306.788.717 1.459 1.384 2.126.667.666 1.336 1.079 2.126 1.384.766.296 1.636.499 2.913.558C8.333 23.988 8.74 24 12 24s3.667-.015 4.947-.072c1.277-.06 2.148-.262 2.913-.558.788-.306 1.459-.718 2.126-1.384.666-.667 1.079-1.335 1.384-2.126.296-.765.499-1.636.558-2.913.06-1.28.072-1.687.072-4.947s-.015-3.667-.072-4.947c-.06-1.277-.262-2.149-.558-2.913-.306-.789-.718-1.459-1.384-2.126C21.319 1.347 20.651.935 19.86.63c-.765-.297-1.636-.499-2.913-.558C15.667.012 15.26 0 12 0zm0 2.16c3.203 0 3.585.016 4.85.071 1.17.055 1.805.249 2.227.415.562.217.96.477 1.382.896.419.42.679.819.896 1.381.164.422.36 1.057.413 2.227.057 1.266.07 1.646.07 4.85s-.015 3.585-.074 4.85c-.061 1.17-.256 1.805-.421 2.227-.224.562-.479.96-.899 1.382-.419.419-.824.679-1.38.896-.42.164-1.065.36-2.235.413-1.274.057-1.649.07-4.859.07-3.211 0-3.586-.015-4.859-.074-1.171-.061-1.816-.256-2.236-.421-.569-.224-.96-.479-1.379-.899-.421-.419-.69-.824-.9-1.38-.165-.42-.359-1.065-.42-2.235-.045-1.26-.061-1.649-.061-4.844 0-3.196.016-3.586.061-4.861.061-1.17.255-1.814.42-2.234.21-.57.479-.96.9-1.381.419-.419.81-.689 1.379-.898.42-.166 1.051-.361 2.221-.421 1.275-.045 1.65-.06 4.859-.06l.045.03zm0 3.678c-3.405 0-6.162 2.76-6.162 6.162 0 3.405 2.76 6.162 6.162 6.162 3.405 0 6.162-2.76 6.162-6.162 0-3.405-2.76-6.162-6.162-6.162zM12 16c-2.21 0-4-1.79-4-4s1.79-4 4-4 4 1.79 4 4-1.79 4-4 4zm7.846-10.405c0 .795-.646 1.44-1.44 1.44-.795 0-1.44-.646-1.44-1.44 0-.794.646-1.439 1.44-1.439.793-.001 1.44.645 1.44 1.439z"/></svg>
                  </a>
                </div>
              </div>
            </div>
          </div>

          <!-- Google Maps -->
          <div class="glass-card p-2 overflow-hidden h-[500px] group rounded-3xl relative hover:shadow-2xl hover:shadow-primary/10 transition-all duration-500">
            <div class="absolute inset-0 bg-gradient-to-br from-primary/5 to-blue-500/5 opacity-0 group-hover:opacity-100 transition-opacity duration-500 pointer-events-none blur-xl"></div>
            <iframe 
              src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3595.5!2d85.21!3d25.688!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x39ed59c2d0000000%3A0x0!2sTathagat%20Gas%20Agency%2C%20Bazar%20Samiti%20Road%2C%20Near%20Mahila%20Thana%2C%20Hajipur%2C%20Bihar%20844101!5e0!3m2!1sen!2sin!4v1706198400000!5m2!1sen!2sin"
              width="100%" 
              height="100%" 
              style="border:0;" 
              allowfullscreen="" 
              loading="lazy" 
              referrerpolicy="no-referrer-when-downgrade"
              class="w-full h-full rounded-lg"
            ></iframe>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup lang="ts">
definePageMeta({
  layout: 'default'
});

// SEO Meta Tags
useHead({
  title: 'About Us - Solergy Systems | Leading Solar Energy Solutions in Bihar',
  meta: [
    {
      name: 'description',
      content: 'Learn about Solergy Systems, Bihar\'s trusted solar energy provider. Meet our director Shubham Singh and discover our commitment to sustainable energy solutions.'
    }
  ]
});
</script>
