
# <c> Enigheten Booking Websites </c>

<i style="font-size: 12px;"><b> Daniel Kertsmik </b>- admin@dankert.store</i>

<style>

* {
    font-family: "Helvetica", Arial, sans-serif;
    background-color: #1e1e1e !important;
    color: #e1e1e1 ;
    -webkit-print-color-adjust: exact;
}

html {
  -webkit-print-color-adjust: exact;
}

body {
    padding: 100px;
    border: 50px solid #yellow
}

table {
    width: 70vw;
}

i   {
    padding-left: 30px;
}

c {
    color: #e1e1e1;
}

inv {
    opacity: 0;
}

</style>


## <c>Table of contents </c>

-   1. <a href="#revision-history"> Revision history </a>
-   2. <a href="#introduction">Introduction</a>
    -  <a href="#glossary"> 1.1. Glossary (All the weird / short for words) </a>
    -  <a href="#references"> 1.2. References (Every external reference made) </a>
    -  <a href="#purpose"> 1.3. Purpose (What the document is for and the project short description)</a>
-   3. <a href="#features"> Features (Explain simply what the website will have) </a>
        - <a href="#design"> 3.1. Design (How the website looks like) </a>
-   4. Requirements (How the features function)
    -   4.1. Functional requirements (How the website has to function)
    -   4.2. Users (User stories how the can interact with the system)
        -   4.2.1. Customer
        -   4.2.2. Administrator
        -   4.2.3. Worker
        -   4.2.4. Other
        4.2. Non-functional requirements (How the website should function)
-   5. Risk (Explaining all the risks)
-   6. Gain (Explain the gains for the hotel)
-   7. Other
-   8. Conclusion

<inv>x
x
x
x
</inv>

## <c id="revision-history">1. Revision history </c>
<!--Documentation history and what the current version is.-->
<table>
<tr>
<th><c>Version                  </c></th>
<th><c>Date                     </c></th>
<th><c>Description of Changes   </c></th>
</tr>
<tr>
<td>V1                  </td>
<td>2023.02.15                </td>
<td>Exploration        </td>
</tr>
<tr>
<td>V2                  </td>
<td>2023.02.17               </td>
<td>Early Publishing    </td>
</tr>
<tr>
<td>-                  </td>
<td>-                </td>
<td>-       </td>
</tr>
</table>

<p>© 2023, Daniel Kertsmik </p>

## <c id="introduction">2. Introduction</c>

## <c id="glossary"><i>2.1. Glossary </i></c>

<table>
<tr>
<th><c> Term            </c></th>
<th><c> Definition      </c></th>
</tr>
<tr>
<td>admin    </td>
<td>The one that has access to all the administrative functions and manages the system.      </td>
</tr>
<tr>
<td>customer    </td>
<td>A individual that wants to book a room.            </td>
</tr>
</table>

## <c id="references"><i> 2.2. References </i></c>

This is the current address enigheten.ax

## <c id="purpose"><i>2.3. Purpose </i></c>


This document aims to:

- Make a blueprint for the Enigheten booking website.
- Explains technical aspects of the website.
- List risks and profits.
- Who does what in the system?
- The look an accessibility of the website

## <c id="features">3. Features </c>

- Sirvoy booking system webhook.
  ![sirvoy](../sirvoybooking.png)
- Stripe payment system connected to sirvoy. 
  ![sirvoystripe](../sirvoystripe.png)
  <div style="display: flex; justify-content: center;">

  ![stripe](../stripe.png)
  </div>
- Google Maps location webhook.
  ![google](../googlewebhook.png)

## <c id="design"><i> 3.1. Design </i></c>
