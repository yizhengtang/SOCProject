---
layout: home
title: FPGA VGA Driver Project
tags: fpga vga verilog
categories: demo
---

Welcome to my FPGA VGA Driver Project. For this project I tried to design and implement a "Mercedes Benz Logo" display using Verilog, demonstrating the use of geometric shapes like circles and triangles on an FPGA-driven VGA Display.

## **Template VGA Design**
### **Project Set-Up**
This project was developed using the Basys3 FPGA development board and Vivado design software. The setup includes creating a VGA driver capable of rendering pixels on a 640x480 resolution display. The design flow involved writing Verilog code for pixel generation, simulating the design, synthesizing the hardware description, and implementing it on the Basys3 board.


The image below is an example of my Vivado project summary window:

<img src="https://raw.githubusercontent.com/melgineer/fpga-vga-verilog/main/docs/assets/images/VGAPrjSum.png">

### **Template Code**

The provided Verilog templates included modules for:
1. **VGA Sync Generation**: This module generates the necessary horizontal and vertical synchronization signals to control the VGA display at a resolution of 640x480 pixels.
2. **Pixel Generation**: A simple color pattern (e.g., stripes or a solid background) was generated by controlling the RGB outputs based on pixel positions (`col` and `row`).

The VGA interface operates by scanning through each pixel row by row, synchronizing the timing signals to ensure the display is refreshed at 60Hz. A horizontal sync signal (H-Sync) and a vertical sync signal (V-Sync) are generated for proper image display.

### **Simulation**
Explain the simulation process. Reference any important details, include a well-selected screenshot of the simulation. Guideline: 1/2 short paragraphs.
### **Synthesis**
Describe the synthesis and implementation processes. Consider including 1/2 useful screenshot(s). Guideline: 1/2 short paragraphs.
### **Demonstration**
Perhaps add a picture of your demo. Guideline: 1/2 sentences.

## **My VGA Design Edit**
Introduce your own design idea. Consider how complex/achievabble this might be or otherwise. Reference any research you do online (use hyperlinks).
### **Code Adaptation**
Briefly show how you changed the template code to display a different image. Demonstrate your understanding. Guideline: 1-2 short paragraphs.
### **Simulation**
Show how you simulated your own design. Are there any things to note? Demonstrate your understanding. Add a screenshot. Guideline: 1-2 short paragraphs.
### **Synthesis**
Describe the synthesis & implementation outputs for your design, are there any differences to that of the original design? Guideline 1-2 short paragraphs.
### **Demonstration**
If you get your own design working on the Basys3 board, take a picture! Guideline: 1-2 sentences.

## **More Markdown Basics**
This is a paragraph. Add an empty line to start a new paragraph.

Font can be emphasised as *Italic* or **Bold**.

Code can be highlighted by using `backticks`.

Hyperlinks look like this: [GitHub Help](https://help.github.com/).

A bullet list can be rendered as follows:
- vectors
- algorithms
- iterators

Images can be added by uploading them to the repository in a /docs/assets/images folder, and then rendering using HTML via githubusercontent.com as shown in the example below.

<img src="https://raw.githubusercontent.com/melgineer/fpga-vga-verilog/main/docs/assets/images/VGAPrjSrcs.png">