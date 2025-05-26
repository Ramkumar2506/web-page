# web-page
    <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Healthcare Dashboard</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-50">
  <div class="grid grid-cols-12 gap-4 p-4 min-h-screen">
    <!-- Sidebar -->
    <div class="col-span-2 bg-white rounded-2xl shadow-md p-4 space-y-6">
      <h1 class="text-xl font-bold text-blue-700">Healthcare.</h1>
      <nav class="space-y-4 text-gray-700">
        <div class="font-semibold text-blue-600">Dashboard</div>
        <div>History</div>
        <div>Calendar</div>
        <div>Appointments</div>
        <div>Statistics</div>
        <div>Chat</div>
        <div>Support</div>
      </nav>
    </div>

    <!-- Main Dashboard -->
    <div class="col-span-10 grid grid-cols-3 gap-4">
      <!-- Body Overview -->
      <div class="col-span-1 bg-white rounded-2xl shadow-md p-4">
        <h2 class="font-bold text-lg mb-2">Dashboard</h2>
        <div class="relative">
          <img src="https://i.ibb.co/wdpG4z0/human-body.png" alt="Human Body" class="w-full" />
          <div class="absolute top-1/3 left-1/3 bg-red-200 text-red-800 px-2 py-1 rounded-xl text-xs">
           <U+2764><U+FE0F>Healthy Heart
          </div>
          <div class="absolute bottom-1/4 left-1/4 bg-blue-200 text-blue-800 px-2 py-1 rounded-xl text-xs">
            💪 Healthy Leg
          </div>
        </div>
      </div>

      <!-- Appointments Summary -->
      <div class="col-span-1 bg-white rounded-2xl shadow-md p-4">
        <h3 class="text-md font-semibold mb-4">Appointments</h3>
        <div class="space-y-2">
          <div class="flex justify-between">
            <div>Lungs</div><span class="text-xs text-gray-500">26 Oct 2021</span>
          </div>
          <div class="flex justify-between">
            <div>Teeth</div><span class="text-xs text-gray-500">26 Oct 2021</span>
          </div>
          <div class="flex justify-between">
            <div>Bone</div><span class="text-xs text-gray-500">26 Oct 2021</span>
          </div>
        </div>
      </div>

      <!-- Calendar & Schedule -->
      <div class="col-span-1 bg-white rounded-2xl shadow-md p-4">
        <div class="flex justify-between items-center mb-2">
          <h3 class="font-semibold">October 2021</h3>
          <button class="text-sm border px-2 py-1 rounded">+</button>
        </div>
        <div class="grid grid-cols-7 text-xs text-center gap-y-1">
          <!-- Sample static days -->
          <div class="p-1 rounded bg-blue-100 text-blue-800">25</div>
          <div class="p-1">26</div>
          <div class="p-1">27</div>
          <div class="p-1">28</div>
          <div class="p-1">29</div>
          <div class="p-1">30</div>
          <div class="p-1">31</div>
        </div>
        <div class="space-y-2 mt-4">
          <div class="bg-blue-100 p-2 rounded-md text-sm">
           🦷 Dentist 9:00-11:00 <br /> Dr. Cameron Williamson
          </div>
          <div class="bg-purple-100 p-2 rounded-md text-sm">
        Physiotherapy 11:00-12:00 <br /> Dr. Kevin Djones
          </div>
        </div>
      </div>

      <!-- Schedule -->
      <div class="col-span-2 bg-white rounded-2xl shadow-md p-4">
        <h3 class="font-semibold mb-4">The Upcoming Schedule</h3>
        <div class="grid grid-cols-2 gap-4 text-sm">
          <div class="space-y-2">
            <div class="bg-gray-100 p-2 rounded">Health checkup complete - 11:00 AM</div>
            <div class="bg-gray-100 p-2 rounded">Ophthalmologist - 14:00 PM</div>
          </div>
          <div class="space-y-2">
            <div class="bg-gray-100 p-2 rounded">Cardiologist - 12:00 AM</div>
            <div class="bg-gray-100 p-2 rounded">Neurologist - 16:00 PM</div>
          </div>
        </div>
      </div>

      <!-- Activity -->
      <div class="col-span-1 bg-white rounded-2xl shadow-md p-4">
        <h3 class="font-semibold mb-2">Activity</h3>
        <div class="flex space-x-1 items-end h-24">
          <div class="w-3 h-12 bg-blue-400 rounded"></div>
          <div class="w-3 h-16 bg-blue-400 rounded"></div>
          <div class="w-3 h-10 bg-blue-400 rounded"></div>
          <div class="w-3 h-20 bg-blue-400 rounded"></div>
          <div class="w-3 h-14 bg-blue-400 rounded"></div>
          <div class="w-3 h-18 bg-blue-400 rounded"></div>
          <div class="w-3 h-8 bg-blue-400 rounded"></div>
        </div>
      </div>
    </div>
  </div>
</body>
</html>


