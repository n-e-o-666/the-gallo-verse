# The Gallo-Verse

- [The Gallo Verse](#the-gallo-verse)
  * [General Info](#general-info)
  * [The x, y coordinates](#the-x--y-coordinates)
  * [Edit the correct file](#edit-the-correct-file)
  * [Your outside-the-loop code](#your-outside-the-loop-code)
  * [Your inside-the-loop code](#your-inside-the-loop-code)
  * [Saving your code](#saving-your-code)
  * [Editing after pull request](#editing-after-pull-request)

## General info
In order to have everyone's code work correctly there are a couple rules you must follow.

Before you start you need to understand the two main places to place your code.

There is code **INSIDE** the game-loop and code **OUTSIDE** the game loop.

![image](https://github.com/MrGallo/the-gallo-verse/assets/11080017/fdcc2e1c-5e4e-4130-b1b5-807075490ed6)

The variables you define **OUTSIDE** the loop should be named with your name at the end. In my case, `whatever_gallo`. This will avoid variable-name clashes with other students in the class. Please also be aware that there might be students with the same name.

## The x, y coordinates
You will eventually be placed somewhere on a grid and your drawing will have to be moved from `x = 0` `y = 0` to somewhere else. This means that every single time you draw something, you **MUST** reference this `x` and `y`. This is quite simple, really, you only need to add `x + ` and `y + ` to all your `x` and `y` values. For example:

```python
# original location (150, 200)
pygame.draw.rect(screen, "blue", (150, 200, 50, 50))

# new location (x + 150, y + 200)
pygame.draw.rect(screen, "blue", (x + 150, y + 200, 50, 50))
```

## Edit the correct file
Ensure you are editing the correct file for your class. 

![image](https://github.com/MrGallo/the-gallo-verse/assets/11080017/d0154f06-be24-4093-928c-94ee6aaedc77)

Click the edit icon and "Fork" the repository

![image](https://github.com/MrGallo/the-gallo-verse/assets/11080017/655633c0-a911-4a76-b9db-647da245e7b0)


## Your outside-the-loop code
Copy your code you have that is **OUTSIDE** the game loop

![image](https://github.com/MrGallo/the-gallo-verse/assets/11080017/1d832625-a88e-4a22-aeee-b4336fbb416d)

Paste it in the Gallo-verse file specific to your class **OUTSIDE** the game loop inside the indicated area.
There will be other people's code in this area, so just add it at the bottom and ensure you don't delete
anyone else's code.

![image](https://github.com/MrGallo/the-gallo-verse/assets/11080017/e22030ab-a4bf-4fa4-b219-ba3fd231cbeb)

## Your inside-the-loop code
Now take your loop code, and paste it at the bottom of the indicated area in the loop. Be aware that other students will have code here, place yours at the bottom and don't delete anyone else's code. Your code must start with the `x` and `y` variables. You can edit them to reflect your position on the grid. Be sure to confirm that your code works before submitting a pull request (below).

![image](https://github.com/MrGallo/the-gallo-verse/assets/11080017/4484cf85-1212-49a3-812f-fe996b4de274)


## Saving your code
To save and submit your changes, click "Commit changes" (top right).

![image](https://github.com/MrGallo/the-gallo-verse/assets/11080017/b997e051-bc32-4655-81ec-07a098298446)

When you complete the commit, you will be brought to a summary page where you can submit a pull request, which is a request for me to pull your changes into my version. Confirm it is able to merge, and then click "Create pull request".

![image](https://github.com/MrGallo/the-gallo-verse/assets/11080017/4a781213-1395-4e4f-aa12-8663c201f874)

Add a title and a description before clicking "Create pull request" one last time.

![image](https://github.com/MrGallo/the-gallo-verse/assets/11080017/bd8f1199-97c6-46e6-bc38-2cbceca2bf4c)

## Editing after pull request
You can edit the pull request code directly if you need to. Just go to 1. "Files Changed", and then 2. the three dots and 3. "Edit file"

![image](https://github.com/MrGallo/the-gallo-verse/assets/11080017/76edead7-942e-48f2-9ed9-cd699d41ec2d)

