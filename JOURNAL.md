## All 3D Printed FTC Drivetrain
----
```
Title: 3DP Drivetrain

Author: ryan d

Description: A FTC Drivetrain using as many 3d printed parts to crate the most customizable, durable, and CHEAP as possible

Created: 6-21-2025

Time spent: 24 hours
```
----

# 6-19-2025 - 8 Hours
## Layout

I started with getting the top mounting rails down. These are designed to have a 48mm gap between the two, as to mount any gobilda products that follow that standard. They can also hold any other mounting hardware that we need, as it will be easy to just print mounting hardware

![88L7ImE](https://github.com/user-attachments/assets/06e92385-423c-4e71-b3e2-8ecbdbaa7a1d)

After that, I went onto the wheel placement, and I just made sure that they had enough ground clearance with a 108mm height for the whole assembly.

![Fusion360_DaYXXIthQX](https://github.com/user-attachments/assets/f45ab18f-624d-4097-8df4-231529d1f1d3)

## Modeling

Then, I added the Grid Munting system, all alligned on 8mm grid to work with gobilda parts (What we use for the most part)

![Fusion360_X9xPGkcogC](https://github.com/user-attachments/assets/d44bf763-96e3-4ed9-977b-426169aa18a4)

Mounting points to attach the two pods of the drivetrain togeather to form a half. It had to be split in order to fit on one printbed, and simply bolting the two togeather is the most effective way to do so.

![Fusion360_Sx9Qb9Y8nO](https://github.com/user-attachments/assets/1b5f9efc-2f31-4b08-89c4-82262544ad00)

The part was mirrored  to create the mostly finished pod

![Fusion360_dO0HVU8Hnw](https://github.com/user-attachments/assets/efad6e19-1da8-42cb-b3c9-4db014ea71d0)

---- 

# 6-20-2025 - 6 Hours
## Motors

I got the pulley for the HTD 3 Belt imported, and then alligned it with the best spacing for a 100 tooth belt, and got the motor alligned to find the right place for a mount

![Fusion360_YkTrWI9q8y](https://github.com/user-attachments/assets/75b5b5f9-ea2e-4f29-9ac9-6c2a16a8bc8d)

Next cam a mount for the motor, and with a clamping mount and bearing support on the extririor wall, it will have plenty of support. For now, I am just using 435 motors on a 1:1 but it will be easy enoughh to change that if that is deemed inadaquit.

![Fusion360_fJ4oJ7ra5m](https://github.com/user-attachments/assets/d195b2e7-9985-4483-94a0-2b40d4bc1c69)

The cover for the motors is both a protective mesure, and the main structural brace for the robot. It will be the connection between the two halves of the chassis, eventualy provinding wire management, and hub, odo, and battery mounts.

![Fusion360_ghwo6ZCcd7](https://github.com/user-attachments/assets/c1bf1ef4-f203-4df9-a7da-1fe6c81f7784)

![Fusion360_UiN48u3bqZ](https://github.com/user-attachments/assets/b10da07f-4806-43d8-9bf0-bd53ba7e2067)

I spent the rest of the time further refining and ended up with this:

![Fusion360_99nrl9oc8i](https://github.com/user-attachments/assets/f6254c36-517f-4322-acd2-595d5580fb76)

The full assembly so far:

![Fusion360_uBIizt1Rju](https://github.com/user-attachments/assets/f876338e-98c8-4dfe-8316-df601fb08057)

----
# 6-21-2025 - 4 Hours
## FEA

This is the coolest part by far, its a bunch of simulations and the coolest looking models ever. As a bonus they have some useful info.

I did several simulations in fusion to test if this design could acctualy take the forces it would expirience in competitions, so I decided on doing a first simulation of forces pushing the two halves appart from the top.

----

Setup: 


![Fusion360_VxilaGZbVu](https://github.com/user-attachments/assets/8e3d0988-590f-4ae7-b2da-babff7319531)

Displacement:


![Fusion360_l8kNUF9FA9](https://github.com/user-attachments/assets/d9fc49c3-0b10-405f-ae30-002d705f7a58)

Stress:


![Fusion360_3vuXtYZTeW](https://github.com/user-attachments/assets/f8609b24-7e04-403c-84a6-578e279bf98f)

----

With less than half a mm from 100 neutons, this is more than satisfactory. for lateral stresses, this drivetrain will be more than capable of withstanding most anything, especialy because plastics, and PLA in particular are incredibly impact resistand. If necisary we could try to print it in TPU, just for that near invulrability

Then the vertical loads:

----

Setup:

![Fusion360_K4OMfoFxmH](https://github.com/user-attachments/assets/08fbe2fb-8ccb-4291-88db-646f9bcda432)

Displacement:


![Fusion360_Ucz5qTIiVf](https://github.com/user-attachments/assets/1d9a4ec3-25e4-4e07-81df-9d068416f415)

Stress:


![Fusion360_LewLiQoi0W](https://github.com/user-attachments/assets/c23dc5e9-a2a9-4203-a005-b121b51a04e3)

----

Again, more than enough. This load was 125 N, and with that little deflection, this will be a plenty rigid, and much mor importantly, an incredibly strong chassis.

# 6-22-2025 - 6 hours
## BOM

I spent some time just getting the BOM formmated, and getting all of the parts loaded in, and wow did I underestimate the cost, the preliminary cost was around $200, but after taking off some of the bearings, and estimating what we would have avalable, I got the total down to around $150, but that is still way to expensive, so i decided to try and eliminate the motor clamping mounts first, as they were $40 alone.


## CAD & FEA

I just modeled a basic replacement, that has an extra set of holes to bolt them togeather.

![F2KI6HQ9Af](https://github.com/user-attachments/assets/af78f415-7f69-4303-808f-2500fec769c6)

Then I just ran a couple of simulations to eliminate weakpoints, and ended up with very promising results.

----

Setup:

![Fusion360_rUoUMmScyy](https://github.com/user-attachments/assets/ec75362e-5d60-413c-a890-2d7a3279877d)

Displacement:

![Fusion360_jduuymUyhZ](https://github.com/user-attachments/assets/9c0826fb-9f15-4cd4-90d2-93ece7af0ef8)

Strain:

![Fusion360_fNPN24BdQP](https://github.com/user-attachments/assets/ddb23791-7943-486f-93b2-f82c0486f262)

----

I also redesigned the motor cover/brace:

![Fusion360_h0JIOzbhoG](https://github.com/user-attachments/assets/1de62919-f570-492b-ba34-477da01b59bb)


Started a render on fusion, idk how long imma give it.





