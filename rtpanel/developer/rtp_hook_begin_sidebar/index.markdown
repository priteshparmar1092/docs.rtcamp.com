---
title: rtp_hook_begin_sidebar
---

### Description


Adds content at the beginning of the Sidebar (#sidebar).


### Example



    
    function custom_hook_begin_sidebar() { ?>
    <p>This is at the beginning of the Sidebar</p><?php
    }
    add_action( 'rtp_hook_begin_sidebar', 'custom_hook_begin_sidebar' );
