<!-- ╔══════════════════════════════ BEG ══════════════════════════════╗ -->

<br>
<div align="center">
    <p>
        <img src="./assets/img/logo.png" alt="logo" style="" height="80" />
    </p>
</div>

<div align="center">
    <img src="https://img.shields.io/badge/v-{{version}}-black"/>
    <a href="{{author_url}}">
    </a>
    <a href="{{homepage}}"> <img src="https://img.shields.io/badge/{{tag-badge}}-black"/> </a>
</div>

<div align="center">
    <img src="./assets/img/line.png" alt="line" style="display: block; margin-top:20px;margin-bottom:20px;width:500px;"/>
    <br>
</div>

<!-- ╚═════════════════════════════════════════════════════════════════╝ -->



<!-- ╔══════════════════════════════ DOC ══════════════════════════════╗ -->

- ## Quick Start 🔥

    - ### Pre

        ```bash
        # clone
        space init <name> --type lib

        # setup
        cd <name>       # enter the project dir
        space install   # install the dependencies if exists

        # manage
        space test      # run the tests
        space build     # create `/dist/..`
        space start     # build and start `/dist/main.js`
        space publish   # to publish on `npm`
        ```

    - ### Usage

        ```bash
        # to install your library after publishing on `npm`
        space i {{tag}}
        ```

        ```ts
        // to import your library after installing via `space`
        // inside `.ts` file
        import * as {{name}} from `{{tag}}`;
        ```

<!-- ╚═════════════════════════════════════════════════════════════════╝ -->



<!-- ╔══════════════════════════════ END ══════════════════════════════╗ -->

<br>
<div align="center">
    <img src="./assets/img/line.png" alt="line" style="display: block; margin-top:20px;margin-bottom:20px;width:500px;"/>
    <br>
</div>
<br>
<div align="center">
    <a href="https://github.com/solution-lib/space"><img src="https://img.shields.io/badge/by-Space-black"/></a>
</div>

<!-- ╚═════════════════════════════════════════════════════════════════╝ -->