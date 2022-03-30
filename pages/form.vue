<template>
  <div class="container bg-gray-100">
    <section class="body-font overflow-hidden">
      <div class="px-5 py-24 mx-auto">
        <div class="lg:w-4/5 mx-auto flex flex-wrap">
          <img
            alt="ecommerce"
            class="
              lg:w-1/2
              w-full
              lg:h-auto
              h-64
              object-cover object-center
              rounded
            "
            src="https://dummyimage.com/200x200"
          />
          <div
            class="
              lg:w-1/2
              w-full
              lg:pl-10 lg:pr-10 lg:py-6
              mt-6
              lg:mt-0
              bg-white
              px-4
            "
          >
            <h1 class="text-gray-900 text-3xl title-font font-medium mb-4">
              Login
            </h1>

            <div class="flex flex-col space-y-4">
              <div class="flex flex-col space-y-2">
                <label class="text-slate-500 font-medium">Email</label>
                <input type="text" class="rounded-lg" placeholder="Email" />
              </div>
              <div class="flex flex-col space-y-2">
                <label class="text-slate-500 font-medium">Password</label>
                <input
                  type="password"
                  class="rounded-lg"
                  placeholder="password"
                />
              </div>
              <div class="flex space-y-2">
                <label class="text-slate-500 font-medium">
                  <input type="checkbox" class="rounded-sm" />
                  Remember me
                </label>
              </div>
              <div class="flex space-y-2">
                <button
                  class="
                    bg-indigo-500
                    p-2
                    rounded-lg
                    hover:bg-indigo-600
                    text-white
                    ring-1
                    font-medium
                  "
                >
                  Submit
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <div class="body-font overflow-hidden mb-4">
      <div class="my-auto px-5 py-10 lg:flex">
        <div class="lg:w-1/2 shadow-lg p-4 rounded-md bg-white">
          <h1 class="text-gray-900 text-3xl title-font font-medium mb-4">
            Personal Information
          </h1>
          <div class="flex flex-col space-y-2">
            <div class="flex flex-col space-y-2">
              <label class="text-black font-medium">Name</label>
              <input type="text" class="rounded-lg" placeholder="Name" />
            </div>
            <div class="flex flex-col space-y-2">
              <label class="text-black font-medium">Address</label>
              <input type="text" class="rounded-lg" placeholder="Address" />
            </div>
            <div class="flex flex-col space-y-2">
              <label class="text-black font-medium">Phone</label>
              <input type="text" class="rounded-lg" placeholder="Phone" />
            </div>
            <div class="flex flex-col space-y-2">
              <label class="text-black font-medium">Content</label>
              <textarea
                class="rounded-lg"
                rows="2"
                placeholder="Content"
              ></textarea>
            </div>
          </div>
        </div>
        <div class="lg:w-1/2 p-4">
          lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
</style>