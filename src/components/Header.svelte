<style>
    .btn-primary {
        background: #ff9900;
        border: 0;
        padding: 15px 40px 15px 40px;
        font-size: 16px;
        font-weight: bold;
    }

    .btn-primary:hover {
        background: rgb(219, 133, 4);
        border: 0;
    }

    .btn-secondary {
        background: none;
        border: 1px solid #bcd0e5;
        padding: 15px 40px 15px 40px;
        font-size: 16px;
        font-weight: bold;
        color: #173a56;
    }

    .btn-secondary:hover {
        background: none;
        border: 1px solid rgb(159, 177, 197);
        color: #173a56;
    }

    .navbar-nav .nav-link {
        color: #2f281e;
    }
</style>

<!-- svelte-ignore a11y-invalid-attribute -->
<nav class="navbar py-4 navbar-expand-lg navbar-light">
    <div class="container">
        <a class="navbar-brand" href="#">
            <img src="assets/images/logo.png" width="187" alt="" />
        </a>
        <button
            class="navbar-toggler"
            type="button"
            data-toggle="collapse"
            data-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation">
            <span class="navbar-toggler-icon" />
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active align-self-center">
                    <a class="nav-link" href="#">Product
                        <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item align-self-center">
                    <a class="nav-link" href="#">Customers</a>
                </li>
                <li class="nav-item align-self-center">
                    <a class="nav-link" href="#">Pricing</a>
                </li>
                <li class="nav-item align-self-center">
                    <a class="nav-link" href="#">Resources</a>
                </li>
                <a
                    class="btn px-4 btn-secondary ml-5"
                    href="#"
                    role="button">Sign In</a>
                <a class="btn px-4 btn-primary ml-2" href="#" role="button">Sign
                    Up</a>
            </ul>
        </div>
    </div>
</nav>
