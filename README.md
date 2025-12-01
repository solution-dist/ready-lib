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
<br>

<!-- ╚═════════════════════════════════════════════════════════════════╝ -->



<!-- ╔══════════════════════════════ DOC ══════════════════════════════╗ -->

- ## Quick Start 🔥

    > _**The simplest, fastest, most organized and stable way to build libraries and packages.**_

    - ### Usage

        - #### Setup

            > install [`space`](https://github.com/solution-lib/space) first.

            - ##### Create

                ```bash
                > space init <name> -t lib    # This will clone this repo and make some changes to suit your lib.
                > cd <name>                   # Go to the project directory
                > space install               # Install the dependencies
                ```

            - ##### Manage

                ```bash
                > space build         # To build your lib
                > space test          # To test  your lib
                > space start         # To start your lib
                > space publish       # To publish on `npm`
                ```

            - ##### Fianlly

                ```bash
                # to install your library after publishing on `npm`
                space i {{tag}}
                ```

                ```ts
                // to import your library after installing via `space`
                import * as {{name}} from `{{tag}}`;
                ```

        <div align="center"> <img src="./assets/img/line.png" alt="line" style="display: block; margin-top:20px;margin-bottom:20px;width:500px;"/> <br> </div>

        - #### Structure

            - ##### Root

                ```bash
                ┣ assets        # The assets folder
                ┃ ┗ ...
                ┃
                ┣ dist          # The distribution folder
                ┃ ┗ ...
                ┃
                ┣ src           # The source-code folder
                ┃ ┗ main.ts    # The main entry point file
                ┃
                ┣ test          # The tests folder
                ┃ ┗ ...
                ┃
                ┗ .space        # The space configuration file

                # You can safely hide/ignore the rest of files.
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