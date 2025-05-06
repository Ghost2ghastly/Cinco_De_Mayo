<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cinco De Mayo</title>
    <style>
    :root {
        --green: #089d0d;
        --white:#f0e6e6;
        --red: #d70000;
        --shadow: 0 4px 12px rgba(0,0,0, .45)
    }
    * {
        margin: 0
        box-sizing: border-box;
    }

    body {
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 0 1rem;
    }
    header{
        background: linear-gradient(90deg, var(--green), var(--white), var(--red));
        color: #483e3e;
        border-radius: .3rem;
        box-shadow: var(--shadow);
        transition: transform .2s;
    }
    header:hover {
        transform: scale(1.05);
    }
    main{
        width: 100%;
        max-width: 700px;
    }
    footer{
        margin: 2rem;
        color: #666;
        font-size: 0.7rem;
    }
    details{
        background: #cacaca;
        border-radius: .6rem;
        box-shadow: var(--shadow);
        margin: 1rem 0;
        font-size: 1.2rem;

    }

    details[open]{
        outline: 2px solid var(--green);
    }

    summary{
        cursor: pointer;
        font-weight: 600;
    }
    img{
        width: 500px;
        border-radius: .6rem 0;
        margin: 1rem 0;
        object-fit: cover
    }
    ol {
        padding-left: 1.3rem;
    }
    </style>
</head>
<body>
    <header> 
        <H1>CINCO DE MAYO FIESTA!</H1>
        <p>5 de mayo, Job Corps, Mexico</p>
    </header>
    <main>
        <!-- content coming soon -->
          <!--ACCORDION 1  -->
        <details>
            <summary>why do we celebrate</summary>
            <p>Cinco De Mayo marks the day when the mexicans beat the french</p>
        </details>
        <!-- ACCORDION 2 -->
        <details>
            <summary>Quick Taco Reciper</summary>
            <img src="data:image/jpeg;base64,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" alt="Taco Recipe">
            <ol>
                <li>Shredded Chicken</li>
                <li>Warm Tortilla</li>
                <li>Put salsa, onions and cilantro</li>
                <li>Enjoy your Taco</li>
            </ol>
        </details>
    </main>
    <footer>
        Viva Mexico &copy 2025
    </footer>
</body>
</html>
