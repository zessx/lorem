Lorem
=====

Lorem Ipsum generator with a mini API.

How to use ?
------------

Use `{n}` (a single number) to generate a section with `n` words :

    lorem.domain.tld/10
    /*
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non.
    */

Use `{p}x{n}` to generate `p` sections with `n` words :

    lorem.domain.tld/3x5
    /*
    Lorem ipsum dolor sit amet.
    Ut velit mauris, egestas sed.
    Aliquam convallis sollicitudin purus. Praesent.
    */
    
Use `{n}+{m}` to generate a section with `n` words, followed by a section with `m` words :

    lorem.domain.tld/5+15
    /*
    Lorem ipsum dolor sit amet.
    Ut velit mauris, egestas sed, gravida nec, ornare ut, mi. Aenean ut orci vel massa.
    */
    
You can combine `+` and `x` as much as you want :

    lorem.domain.tld/2x5+3x10+2x15
    /*
    Lorem ipsum dolor sit amet.
    Ut velit mauris, egestas sed.
    Aliquam convallis sollicitudin purus. Praesent aliquam, enim at fermentum mollis, ligula massa adipiscing nisl, ac.
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non risus. Suspendisse lectus tortor, dignissim.
    Ut velit mauris, egestas sed, gravida nec, ornare ut, mi. Aenean ut orci vel massa.
    Aliquam convallis sollicitudin.
    Lorem ipsum dolor.
    */
  
An invalid input string will get rewritten to the default input string : `123+102+70`. 

    lorem.domain.tld
    /*
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non risus. Suspendisse lectus tortor, dignissim sit amet, adipiscing nec, ultricies sed, dolor. Cras elementum ultrices diam. Maecenas ligula massa, varius a, semper congue, euismod non, mi. Proin porttitor, orci nec nonummy molestie, enim est eleifend mi, non fermentum diam nisl sit amet erat. Duis semper. Duis arcu massa, scelerisque vitae, consequat in, pretium a, enim. Pellentesque congue. Ut in risus volutpat libero pharetra tempor. Cras vestibulum bibendum augue. Praesent egestas leo in pede. Praesent blandit odio eu enim. Pellentesque sed dui ut augue blandit sodales. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Aliquam nibh. Mauris ac mauris sed pede pellentesque fermentum. Maecenas adipiscing ante non diam sodales.
    Ut velit mauris, egestas sed, gravida nec, ornare ut, mi. Aenean ut orci vel massa suscipit pulvinar. Nulla sollicitudin. Fusce varius, ligula non tempus aliquam, nunc turpis ullamcorper nibh, in tempus sapien eros vitae ligula. Pellentesque rhoncus nunc et augue. Integer id felis. Curabitur aliquet pellentesque diam. Integer quis metus vitae elit lobortis egestas. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Morbi vel erat non mauris convallis vehicula. Nulla et sapien. Integer tortor tellus, aliquam faucibus, convallis id, congue eu, quam. Mauris ullamcorper felis vitae erat. Proin feugiat, augue non elementum posuere, metus purus iaculis lectus, et tristique ligula justo vitae.
    Aliquam convallis sollicitudin purus. Praesent aliquam, enim at fermentum mollis, ligula massa adipiscing nisl, ac euismod nibh nisl eu lectus. Fusce vulputate sem at sapien. Vivamus leo. Aliquam euismod libero eu enim. Nulla nec felis sed leo placerat imperdiet. Aenean suscipit nulla in justo. Suspendisse cursus rutrum augue. Nulla tincidunt tincidunt mi. Curabitur iaculis, lorem vel rhoncus faucibus, felis magna fermentum augue, et ultricies lacus lorem varius purus. Curabitur eu.
    */

Google Chrome integration
-------------------------

You can easily add Lorem to your Google Chrome custom search engines, you'll then be able to quickly use Lorem, writing `lorem <input>` in your Chrome Omnibox.

Legals
------
- Author : [zessx](https://github.com/zessx)
- Licence : [MIT](http://opensource.org/licenses/MIT) 
- Contact : [@zessx](https://twitter.com/zessx)
