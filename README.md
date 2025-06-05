<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>AIOU Student Support Services</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    function toggleAccordion(id) {
      const content = document.getElementById(id);
      content.classList.toggle('hidden');
    }
  </script>
</head>
<body class="bg-gradient-to-b from-green-50 to-white text-gray-800 font-sans">

  <!-- Header -->
  <header class="bg-green-600 text-white py-8 shadow-md">
    <div class="max-w-5xl mx-auto px-4">
      <h1 class="text-3xl font-bold">🎓 AIOU Student Support Services</h1>
      <p class="mt-2 text-lg">Assistance at Every Step of Your Academic Journey</p>
    </div>
  </header>

  <!-- Main Content -->
  <main class="max-w-4xl mx-auto px-4 py-12 space-y-8">

    <!-- Intro -->
    <section>
      <p class="text-lg">
        Allama Iqbal Open University (AIOU) is dedicated to providing a complete support system for students—helping them succeed from enrollment to graduation. Below are the types of support available to guide you throughout your educational path.
      </p>
    </section>

    <!-- Accordion Sections -->
    <section class="space-y-4">

      <!-- Service Block Template -->
      <div class="border border-green-200 rounded-xl bg-white shadow hover:shadow-lg transition duration-300">
        <button onclick="toggleAccordion('admission')" class="w-full text-left px-6 py-4 font-semibold text-green-700 text-xl focus:outline-none">
          📝 Admission Assistance
        </button>
        <div id="admission" class="px-6 pb-4 hidden">
          <p>AIOU offers a transparent admission process. Students facing confusion can contact the admission office or visit regional centers across Pakistan for help.</p>
        </div>
      </div>

      <div class="border border-green-200 rounded-xl bg-white shadow hover:shadow-lg transition duration-300">
        <button onclick="toggleAccordion('counseling')" class="w-full text-left px-6 py-4 font-semibold text-green-700 text-xl focus:outline-none">
          📚 Academic Counseling
        </button>
        <div id="counseling" class="px-6 pb-4 hidden">
          <p>Academic counselors help students choose the right programs, develop study strategies, prepare for exams, and manage time effectively.</p>
        </div>
      </div>

      <div class="border border-green-200 rounded-xl bg-white shadow hover:shadow-lg transition duration-300">
        <button onclick="toggleAccordion('technical')" class="w-full text-left px-6 py-4 font-semibold text-green-700 text-xl focus:outline-none">
          💻 Technical Support
        </button>
        <div id="technical" class="px-6 pb-4 hidden">
          <p>For issues with the AAGHI LMS Portal—like login, assignment submissions, or errors—students can contact AIOU's technical team through helpline or email.</p>
        </div>
      </div>

      <div class="border border-green-200 rounded-xl bg-white shadow hover:shadow-lg transition duration-300">
        <button onclick="toggleAccordion('tutoring')" class="w-full text-left px-6 py-4 font-semibold text-green-700 text-xl focus:outline-none">
          👩‍🏫 Tutoring Services
        </button>
        <div id="tutoring" class="px-6 pb-4 hidden">
          <p>Students can interact with assigned tutors via LMS for course-related questions. Tutors provide feedback on assignments and exam preparation tips.</p>
        </div>
      </div>

      <div class="border border-green-200 rounded-xl bg-white shadow hover:shadow-lg transition duration-300">
        <button onclick="toggleAccordion('exam')" class="w-full text-left px-6 py-4 font-semibold text-green-700 text-xl focus:outline-none">
          🧾 Exams & Results Help
        </button>
        <div id="exam" class="px-6 pb-4 hidden">
          <p>Students receive help accessing exam schedules, roll number slips, and result updates through the portal and exam support staff.</p>
        </div>
      </div>

      <div class="border border-green-200 rounded-xl bg-white shadow hover:shadow-lg transition duration-300">
        <button onclick="toggleAccordion('career')" class="w-full text-left px-6 py-4 font-semibold text-green-700 text-xl focus:outline-none">
          💼 Career Counseling
        </button>
        <div id="career" class="px-6 pb-4 hidden">
          <p>AIOU helps students with job hunting, resume building, and finding opportunities that align with their academic qualifications.</p>
        </div>
      </div>

      <div class="border border-green-200 rounded-xl bg-white shadow hover:shadow-lg transition duration-300">
        <button onclick="toggleAccordion('regional')" class="w-full text-left px-6 py-4 font-semibold text-green-700 text-xl focus:outline-none">
          ☎️ Helpline & Regional Centers
        </button>
        <div id="regional" class="px-6 pb-4 hidden">
          <p>AIOU helpline supports queries about enrollment, programs, or portal access. Students preferring in-person help can visit regional offices.</p>
        </div>
      </div>

    </section>

    <!-- Conclusion -->
    <section class="mt-12 bg-green-100 border-l-4 border-green-600 p-6 rounded-lg">
      <h2 class="text-2xl font-bold text-green-800 mb-2">✅ Conclusion</h2>
      <p>
        AIOU provides a strong student support system to ensure a successful academic experience. Whether you need academic advice, technical help, or career guidance—AIOU is here to support you every step of the way.
      </p>
    </section>

  </main>

  <!-- Footer -->
  <footer class="text-center text-gray-500 text-sm py-6 border-t mt-10">
    &copy; 2025 AIOU Student Services. All Rights Reserved.
  </footer>

</body>
</html>
