Close a Bootstrap modal with back button
========================================
### Close a bootstrap modal with back button

Simply add the script to your page, you can download it from [here](https://github.com/FranBar1966/bootstrap-5-modal-close-on-back/tree/master/src)

```html
<script src="modal-close-on-back.min.js"></script>
```

Or CDN:

```html
<script src="https://cdn.jsdelivr.net/gh/FranBar1966/bootstrap-5-modal-close-on-back@master/src/modal-close-on-back.min.js"></script>
```

No further action is required.

### See: [Example](https://franbar1966.github.io/bootstrap-5-modal-dynamic/example/)

It can be used in combination with: [modal dynamic](https://github.com/FranBar1966/bootstrap-5-modal-dynamic)

```html
<button
  type="button"
  class="btn btn-primary"
  data-bs-toggle="modal"
  data-bs-target="#exampleModal1"
>
  Simple default modal
</button>

<div class="modal fade" id="exampleModal1" tabindex="-1" aria-labelledby="exampleModal1Label" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h1 class="modal-title fs-5" id="exampleModal1Label">Modal title</h1>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        You can click the Back Button to close this modal.
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
      </div>
    </div>
  </div>
</div>
```
