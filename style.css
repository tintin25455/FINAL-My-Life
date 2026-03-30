/* --- 1. NEW COLOR VARIABLES --- */
:root {
    /* Earthy tones from the screenshot */
    --hero-bg-light: #c2a785; 
    --hero-bg-dark: #6e553f;
    --nav-bg: #ffffff;
    --text-main: #ffffff;
    --btn-bg: #4a3a2a;
    
    /* Keeping your old variables for the rest of the site */
    --primary-bg: #f4f4f4;       
    --text-color: #2d3436;       
    --card-bg: #ffffff;          
    --quote-bg: #fdfffe;         
}

/* --- 2. NAVIGATION BAR --- */
.top-nav {
    background-color: var(--nav-bg);
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 50px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    position: sticky;
    top: 0;
    z-index: 100;
}

.logo {
    font-weight: bold;
    font-size: 1.2rem;
    color: #555;
    letter-spacing: 1px;
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 20px;
    align-items: center;
}

.nav-links a {
    text-decoration: none;
    color: #555;
    font-size: 0.9rem;
    font-weight: 500;
}

.nav-links a:hover {
    color: var(--hero-bg-dark);
}

/* --- 3. HERO SECTION LAYOUT --- */
.hero-section {
    background: linear-gradient(135deg, var(--hero-bg-light) 30%, var(--hero-bg-dark) 100%);
    color: var(--text-main);
    padding: 80px 20px;
    min-height: 60vh;
    display: flex;
    align-items: center;
}

.hero-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap; /* Helps with mobile responsiveness */
    width: 100%;
    max-width: 1000px;
}

/* --- 4. LEFT SIDE: TEXT --- */
.hero-text {
    flex: 1;
    min-width: 300px;
    padding-right: 40px;
}

.hero-text h1 {
    font-size: 3.5rem;
    margin: 10px 0;
    text-shadow: none;
}

.hero-text .subtitle {
    font-size: 1.5rem;
    font-weight: 400;
    border-right: 3px solid #dbb892; /* The vertical line accent */
    display: inline-block;
    padding-right: 15px;
    margin-bottom: 20px;
    color: #f1f1f1;
}

.hero-text .description {
    font-size: 0.95rem;
    line-height: 1.8;
    margin-bottom: 30px;
    color: #e0e0e0;
    max-width: 400px;
}

.hero-btn {
    background-color: var(--btn-bg);
    color: white;
    padding: 12px 25px;
    text-decoration: none;
    border-radius: 25px;
    font-weight: bold;
    transition: background 0.3s;
}

.hero-btn:hover {
    background-color: #2b2118;
}

/* --- 5. RIGHT SIDE: IMAGE & RINGS --- */
.hero-visual {
    flex: 1;
    display: flex;
    justify-content: center;
    align-items: center;
    position: relative;
    min-width: 300px;
    height: 350px;
}

.hero-profile-photo {
    width: 220px;
    height: 220px;
    border-radius: 50%;
    object-fit: cover;
    position: relative;
    z-index: 3; /* Keeps image above rings */
}

/* The magic for the concentric circles */
.ring {
    position: absolute;
    border-radius: 50%;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

.inner-ring {
    width: 270px;
    height: 270px;
    background: rgba(0, 0, 0, 0.15); /* Dark transparent circle */
    z-index: 2;
}

.outer-ring {
    width: 330px;
    height: 330px;
    background: linear-gradient(135deg, rgba(255,255,255,0.2), rgba(0,0,0,0.05));
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    z-index: 1;
}

/* Fix Theme Button to match nav */
#theme-btn {
    padding: 6px 12px;
    background: #f1f1f1;
    border: none;
    color: #333;
    border-radius: 15px;
    cursor: pointer;
    font-weight: bold;
    position: static; /* Removes your old absolute positioning */
}
