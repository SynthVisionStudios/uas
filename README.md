<script src="script.js" defer></script>
<a href="#" class="tombol-menu">
    <span class="garis"></span>
    <span class="garis"></span>
    <span class="garis"></span>
</a>

file style.css 
```css
.tombol-menu {
    position: absolute;
    top: 1.7rem;
    right: 1rem;
    display: none;
    flex-direction: column;
    justify-content: space-between;
    width: 30px;
    height: 20px;
}

.tombol-menu .garis {
    height: 3px;
    background-color: #3f72af;
}

@media screen and (max-width: 991.98px) {
    .logo a {
        display: inline;
    }
    .tombol-menu {
        display: flex;
    }
    nav .menu {
        display: none;
    }
    nav .menu.active {
        display: flex;
    }
    nav ul li {
        width:100%;
        border-bottom:1px solid #333333;
    }
}

