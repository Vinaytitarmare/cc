<script>
    import Navbar from "../navbar/+page.svelte"
</script>
<Navbar/>
<div class="bg-[#051016]   h-screen text-[#76DEE1]">
    <div class="min-h-screen flex items-center justify-center p-6">
        <div class=" shadow-xl rounded-lg p-8 max-w-2xl w-full">
          <div class="text-center mb-6">
            <h1 class="text-3xl font-bold ">Contact Us</h1>
            <p class=" mt-2">We'd love to hear from you! Feel free to reach out.</p>
          </div>
          <div class="space-y-4">
            <!-- Name Input -->
            <div>
              <label for="name" class="block text-sm font-medium ">Your Name</label>
              <div class="mt-1">
                <input type="text" id="name" placeholder="Enter your name" class="w-full border bg-[#071821] border-gray-300 bg- rounded-lg p-3 focus:outline-none focus:ring-2 focus:ring-green-400 focus:border-green-400">
              </div>
            </div>
            <!-- Email Input -->
            <div>
              <label for="email" class="block text-sm font-medium ">Email Address</label>
              <div class="mt-1">
                <input type="email" id="email" placeholder="Enter your email" class="w-full border bg-[#06161d] border-gray-300 rounded-lg p-3 focus:outline-none focus:ring-2 focus:ring-green-400 focus:border-green-400">
              </div>
            </div>
            <!-- Message Input -->
            <div>
              <label for="message" class="block text-sm font-medium ">Your Message</label>
              <div class="mt-1">
                <textarea id="message" rows="4" placeholder="Write your message here" class="w-full border bg-[#06151c] border-gray-300 rounded-lg p-3 focus:outline-none focus:ring-2 focus:ring-green-400 focus:border-green-400"></textarea>
              </div>
            </div>
            <!-- Submit Button -->
            <div class="flex justify-center">
              <button class="w-[300px]  font-semibold rounded-lg py-3 hover:bg-gray-700 transition duration-200">
                Send Message
              </button>
            </div>
          </div>
          <!-- Contact Info -->
          <div class="text-center mt-8">
            <p class=" text-sm">Or reach us directly:</p>
            <p class=" font-medium">Email: support@yourcompany.com</p>
            <p class=" font-medium">Phone: +1 234 567 890</p>
          </div>
        </div>
      </div>
      
</div>