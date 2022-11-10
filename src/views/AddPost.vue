<template>
  <div class="bg-white flex flex-col w-80 p-2 m-2 shadow space-y-2">
    <div>
      <label class="block" for="">เรื่อง</label>
      <input class="border w-full" type="text" />
    </div>

    <div>
      <label class="block" for="">ลิงค์ URL</label>
      <input class="border w-full" type="text" />
    </div>

    <div>
      <label class="block" for="">รายละเอียด</label>
      <textarea class="border w-full" rows="5"></textarea>
    </div>

    <button class="bg-green-400 text-white py-2">บันทึก</button>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
