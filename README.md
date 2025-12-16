# Brian Goodell

## My Work
Most recently, I've been employed in the [Flavell Lab](https://flavell.mit.edu/), where I've both collaborated on work and lead my own research projects.

### [AutoCellLabel Live](https://github.com/briangoodell/AutoCellLabel_Live/tree/main)

<table>
  <tr>
    <td valign="top">
      <p>
        <a href="https://doi.org/10.7554/eLife.108159.1">AutoCellLabeler</a> is a deep convolutional network which achieves very high accuracy on neuron identification in multi-channel fluorescent images. I extend this work by creating a network which is able to achieve high performance on one channel (upper image) instead of 4 at nearly 50 times the speed. This allows for real-time labeling of neurons (lower image), and through a novel method, online trace extraction. This work lays a foundation for new experiments using the real state of the entire animal's brain to extract the basis of biological computation.
      </p>
    </td>
    <td valign="top" align="right" width="320">
      <img src="images/Flavell/ACLL/ACL_raw.png" alt="A raw fluorescent image" width="300" />
      <br />
      <sub><em>A Raw fluorescent volume (single channel slice).</em></sub>
      <br />
      <br />
      <br />
      <img src="images/Flavell/ACLL/ACL_label.png" alt="A raw fluorescent image" width="300" />
      <br />
      <sub><em>A labeled output volume (same slice).</em></sub>
    </td>
  </tr>
</table>


### Nematode Matrix

<table>
  <tr>
    <td valign="top" width="320">
      <img src="images/Flavell/UntitledLaserProject/LaserHeatingDiagram.gif"
           alt="Laser heating demo" width="300" />
      <br />
      <sub><em>The laser power modulates in response to the worm moving.</em></sub>
      <br />
    </td>
    <td valign="top">
      <p>In this novel project, I created a system to provide a precise, but entirely manipulatable artificial environment to the nematodes under our microscope: a worm's version of The Matrix, if you will.<br />
      To achieve this, we track the worm on our microscope and perform our <a href="https://doi.org/10.1016/j.cell.2023.07.035">standard freely-moving full-brain recording</a>.</p>
    </td>
  </tr>
</table>

That position tracking is still used to keep the worm centered in the field of view, but is now also used to modulate the power of our NIR laser. We specify an environment, say starting at 20°C and increasing 1° for every cm to the right, decreasing the same to the left. As the worm moves around, the system calculates the required laser power to make our Neo experience the temperature it should. This includes the individual oscillations of the head the worm makes while moving, which are sub-mm and less than a few seconds in duration, but vital to their sensory collection and sampling of the environment. Thus, we must both track the head precisely and be able to modulate the temperature on the order of 0.01°C. To achieve this fast control, and temperatures lower than the ambient environment, I developed a novel, but simple, cooling system which is able to provide controllable baseline environmental change without interfering with the microscope imaging wavelengths, laser heating wavelength, tracking camera, or worm.


<div width="320">
    
</div>
<table>
  <tr>
    <td valign="top" width="320">
      <img src="images/Flavell/UntitledLaserProject/LaserHeatingCoolingDiagram.gif"
        alt="Laser heating demo" width="300" />
        <br />
        <sub><em>Cooling allows for simulated temperature decrease.</em></sub>
        <br />
    </td>
    <td valign="top">
      <img src="images/Flavell/UntitledLaserProject/CoolingSlide.jpg"
        alt="Cooling Slide" width="300" />
        <br />
        <sub><em>A custom partially 3D-printed component of the cooling system.</em></sub>
        <br />
    </td>
  </tr>
</table>

### [BrainAlignNet](https://doi.org/10.7554/eLife.108159.1)
In contributing to the BrainAlignNet project, I was able to extend it's application to another entire species. This was relatively straightforward, but still required careful consideration, implementation, and adjustment. Ultimately, it showed that our pipeline was robust and able to be extended to animals in entirely different branches of life (jellyfish) than what it was originally designed for (worms).

<p align="center">
<img src="images/Flavell/BAN/BAN_Figure_6.png" alt="Alt text" width="300"/>
</p>

## Personal Projects
<!-- ### Life -->
#### The Van
Over COVID, I was lucky enough to be able to convert my family's minivan into a camper, with a custom futon, solar panels, and an antenna for robust cellular data. I did all of the futon woodworking, electronics wiring, and general conversion myself, and the trip was transformative. I was able to spend the first half of my first year taking classes online in National Parks, reinforcing my love of nature, but also learning how to act independently, solve problems with limited resources, and ask others for help (and directions).
<div align="center" valign="top">
    <a href="images/RandomProjects/BuffaloClass.jpg">
    <img src="images/RandomProjects/BuffaloClass.jpg" width="300" alt="Pre-jelly" />
    </a>
    <br /><sub><em>I don't normally get this distracted during class</em></sub>
</div>

### Wookworking
I'm an enthusiastic woodworker, reinforced by my 3 and a half years working in a makerspace. I've made furniture, art, and practical components for other projects. I love working with my hands, but also have come to appreciate the precision of CNC and other fabrication technologies.

<table>
  <tr>
    <td align="center" valign="top">
      <a href="images/RandomProjects/LovelandGuy.jpg">
        <img src="images/RandomProjects/LovelandGuy.jpg" width="260" alt="Topic 1" />
      </a>
      <br /><sub><em>The mascot of my uncle's work, made as a gift</em></sub>
    </td>
    <td align="center" valign="top">
      <a href="images/RandomProjects/TrainDominosCenter.jpg">
        <img src="images/RandomProjects/TrainDominosCenter.jpg" width="260" alt="The " />
      </a>
      <br /><sub><em>The land around the same uncle's house, make to be the centerpiece of a train dominos set</em></sub>
    </td>
    <td align="center" valign="top">
      <a href="images/RandomProjects/TableOil.jpg">
        <img src="images/RandomProjects/TableOil.jpg" width="260" alt="The " />
      </a>
      <br /><sub><em>My friend oils a beautiful walnut table as I advise him in the makerspace</em></sub>
    </td>
  </tr>
</table>

<!-- ### Electronics -->
<!-- skip for now -->

### Cooking
I like to experiment in the kitchen, and have been recently focused on Tofu-manipulation. This exciting field has lots of potential to bring in cross-disciplinary work in high-dimensional sauce theory and even advanced breading techniques. My previous work has unfortunately been consumed before publication, but includes collecting wild raspberries and canning my own raspberry jam, making fresh, spiced, warm applesauce (divine!), and annual holiday fudge (which I share with my coworkers... :wink:)
<div align="center" valign="top">
    <a href="images/RandomProjects/PreJelly.jpg">
    <img src="images/RandomProjects/PreJelly.jpg" width="100" alt="Pre-jelly" />
    </a>
    <br /><sub><em>Pre-Jam (the trial batch)</em></sub>
</div>

### Miscalanous Crafting
I've helped a friend create a fake pool ball to propose to his girlfriend (she used to always steal the 6 ball at his house when they were in high school), engraved the mountains around my uncle's house into wine glasses (another gift), sewed, embroidered, and generally just had fun!
<table>
  <tr>
    <td align="center" valign="top">
      <a href="images/RandomProjects/MountainGlass.jpg">
        <img src="images/RandomProjects/MountainGlass.jpg" width="260" alt="A glass with beautifully, expertly, engraved mountains on it. Really makes you want to hire the person who did it" />
      </a>
      <br /><sub><em>The Mountains in Minature</em></sub>
    </td>
    <td align="center" valign="top">
      <a href="images/RandomProjects/ScaryChocolate.jpg">
        <img src="images/RandomProjects/ScaryChocolate.jpg" width="100" alt="Ahh!" />
      </a>
      <br /><sub><em>Ahh!</em></sub>
    </td>
  </tr>
</table>

<!-- ## Hobbies -->