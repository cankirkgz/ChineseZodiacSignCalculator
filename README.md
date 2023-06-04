<h1>Chinese Zodiac Sign Calculator</h1>
    <p>This Java program calculates the Chinese zodiac sign based on the birth year entered by the user. It determines the zodiac sign by performing a modulo calculation on the birth year and mapping it to the corresponding Chinese zodiac sign.</p>
    <h2>Usage</h2>
<ol>
    <li>Make sure you have Java installed on your system.</li>
    <li>Compile the <code>Main.java</code> file using a Java compiler:</li>
    <pre><code>javac Main.java</code></pre>
    <li>Run the compiled program:</li>
    <pre><code>java Main</code></pre>
    <li>Follow the prompt and enter your birth year when requested.</li>
    <li>The program will calculate your Chinese zodiac sign based on the provided birth year and display it on the console.</li>
</ol>

<h2>Requirements</h2>
<ul>
    <li>Java Development Kit (JDK) installed on your system.</li>
</ul>

<h2>How It Works</h2>
<ol>
    <li>The program uses the <code>Scanner</code> class from the <code>java.util</code> package to read user input from the console.</li>
    <li>It prompts the user to enter their birth year.</li>
    <li>The entered birth year is then used to determine the Chinese zodiac sign:</li>
    <ul>
        <li>The birth year is divided by 12, and the remainder (modulo) is obtained.</li>
        <li>Based on the remainder, the program assigns the corresponding Chinese zodiac sign to the <code>zodiac</code> variable.</li>
    </ul>
    <li>The determined Chinese zodiac sign is displayed on the console.</li>
</ol>

<h2>Example</h2>
<pre>
    <code>
    Doğum Yılınızı Giriniz : 1990
    Çin Zodyağı Burcunuz : Horse
</code>
</pre>
<p>In this example, the user entered a birth year of 1990. The program calculated the Chinese zodiac sign to be "Horse" based on the provided birth year.</p>

<h2>Note</h2>
<p>The program assumes that the input value is a valid birth year. Proper input validation is recommended to handle potential errors and ensure the program's reliability.</p>
