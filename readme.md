# Port of GDCustomRaycastVehicle to Unity & FishNet multiplayer client side prediction

This is my attempt at trying to port and adapt an open source Godot SphereCast based vehicle library. You can find the original library at https://github.com/Tobalation/GDCustomRaycastVehicle




Project was done in Unity 2021.3.20f1

Some notes:

- There are two vehicles a Tank and a Truck (change the PlayerPrefab in NetworkManager->PlayerSpawner to Truck/Tank prefabs)
- The vehicle model is much less complex than the RVP port I did previously - so less bandwidth.

---
#### Free assets used

FishNet: https://assetstore.unity.com/packages/tools/network/fish-net-networking-evolved-207815

GDCustomRaycastVehicle: https://github.com/Tobalation/GDCustomRaycastVehicle

---
MIT License

C# Port Copyright (c) 2023 David Dunscombe

Original Copyright (c) 2020 Dan Suwanseree

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
