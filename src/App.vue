<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from '@/components/HelloWorld.vue'
import feather from 'feather-icons';
</script>

<template>
  <header>

    <!-- heading link bar -->
    <div class="shadow">
      <div class="container m-auto flex justify-end text-xs">
        <a href="#" class="link link-hover text-slate-500 p-4">Tentang GudangSayur</a>
        <a href="#" class="link link-hover text-slate-500 p-4">Tentang GudangSayur</a>
        <a href="#" class="link link-hover text-slate-500 p-4">Tentang GudangSayur</a>
      </div>
    </div>

    <!-- Navbar -->
    <div class="navbar container m-auto py-4">
      <div class="flex-none">
        <img alt="Gudang Sayur Logo" class="logo" src="@/assets/logo.svg" />
      </div>
      <div class="flex-1 form-control px-4">
        <input type="text" placeholder="Search" class="input input-bordered w-full">
      </div>
      <div class="flex-none">
        <button class="btn btn-ghost">
          <img alt="Gudang Sayur Logo" class="logo" src="@/assets/shoppingcart.svg" />
        </button>
        <button class="btn btn-ghost">
          <img alt="Gudang Sayur Logo" class="logo" src="@/assets/bel.svg" />
        </button>
        <div class="divider divider-horizontal"></div>
        <div class="dropdown dropdown-end">
          <label tabindex="0" class="btn btn-ghost avatar text-xs">
            <div class="w-10 mr-2 rounded-full">
              <img src="https://api.lorem.space/image/face?hash=33791" />
            </div>
            Toko
          </label>
          <ul tabindex="0" class="mt-3 p-2 shadow menu menu-compact dropdown-content bg-base-100 rounded-box w-52">
            <li>
              <a class="text-xs" href="#">
                <vue-feather size="22" type="shopping-bag"></vue-feather>
                Kunjungi toko
              </a>
            </li>
            <li>
              <a class="text-xs" href="#">
                <vue-feather size="22" type="box"></vue-feather>
                Seller area
              </a>
            </li>
          </ul>
        </div>
        <div class="dropdown dropdown-end">
          <label tabindex="0" class="btn btn-ghost avatar text-xs">
            <div class="w-10 mr-2 rounded-full">
              <img src="https://api.lorem.space/image/face?hash=33791" />
            </div>
            Mr. Mutafa
          </label>
          <ul tabindex="0" class="mt-3 p-2 shadow menu menu-compact dropdown-content bg-base-100 rounded-box w-52">
            <li>
              <a class="text-xs" href="#">
                <vue-feather size="22" type="user"></vue-feather>
                Profile
              </a>
            </li>
            <li>
              <a class="text-xs" href="#">
                <vue-feather size="22" type="settings"></vue-feather>
                Settings
              </a>
            </li>
            <li>
              <a class="text-xs" href="#">
                <vue-feather size="22" type="log-out"></vue-feather>
                Logout
              </a>
            </li>
          </ul>
        </div>
      </div>
    </div>

  </header>

</template>

<style>

@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

body{
  font-family: Poppins;
}

</style>
