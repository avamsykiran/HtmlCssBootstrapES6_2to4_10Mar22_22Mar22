Lab Setup
-------------------------------------------------------

    1. VSCode   IDE
    2. Chrome   Browser
    3. NodeJS   Javascript Runtime

HTML 5
-------------------------------------------------------

    Hyper Text Markup Language
    is designed to create documents that can be shipped across the http protocol.


    A docuemnt generally comprises of paras, headings, iamges, tables,and other
    sort of text content.

    That text content is refered to as 'Hyper Media'.

    Markup is a practise in leterature used to indicate the significance
    of a piece of text. For Eg:

            My manager said "Report to the HR right away".
            
            The TDR (Test Data Report) is ready.

            Mr. Druvraj - the product owner- is here to meet us.

    A symbol is used before the text and after the text to give it a certan
    significance, and that is called marking up.

    In HTML we use soemthing called a tag before and after a piece of text,
    to describe it.

    Any html document 
        1. is said to comprise of elements.
        2. An elment is of four types
            a. pre-processing instruction   <! instruction here>
                                            <!DOCTYPE HTML>        

            b. tag                          <tagName>Tag Content</tagName>
                                            <p>This is a para element.</p>

            c. entity                       &entityCode;
                                            &nbsp;
                                            &larr;

            d. comment                      <!-- comment goes here -->


    <!DOCTYPE HTML>
    <html>
        <head>
            <!-- will carry the meta data like scripts styles and other information-->
        </head>
        <body>
            <!-- will carry the page content -->
        </body>
    </html>

    The html document is contained by a text file with extension '.htm' or '.html'.

    When thee html documents are provided to a browser (chrome/IE/Edge...), the
    browser reads the html docuemtn from top to bottom and generates a memory tree
    called DOM tree, and this process is called Parsing.

    then once parsing is done - once DOM is ready - it is displayed as a formatted
    page on the browser and that process is called rendering.

    Because we have many browsers, each of them must understand the html tag alike,
    and hence standardising the html tags is important.

    The standarizaition of html is a evolving process and due to which we have
    different versions of html standards like
        html 1.0
        html 2
        html 3
        html 4
        html 5

    Each standard has intriduced a few new elements and also has removed a few elements 
    from the prev versions. Thus it is importnat to inform the browser which version of
    html standard we are following, for it adopt to those standards while validating, parsing
    and rendering our docuemnt.

    Html Elements
    ------------------------------------------------------
        Typography
            h1 to h6        heading elements                    block-element
            p               para element                        block-element
            br              line break                          inline-element
            b,u,i           bold underline and italic elements  inline-element
            strong,em       strong and emphasis elements        inline-element
            sup,sub         superscript and subscript elements  inline-element

            div,
            article,section,
            nav,main,
            header,footer   container elements.                 block-elements

            span,aside,date container elements.                 inline-elements

        Lists
            ol      ordered list eleemnt        block-element
                        'ol' has numbered list items
                        'ol' has a 'type' that takes 
                        a value like '1 or a or i or I' 

            ul      un-ordered list element     block-element
                        'ul' has bulleted list itmes
                        'ul' has a 'type' that takes 
                        a value like 'circle or dot or sqaure'                         

            li      list item element           block-element
                        is used as a sub-element of 'ol' and 'ul'
                        and represents a single list item

        Tables
            table                               cellpadding
                                                cellspacing
                                                width,height
                                                border
                caption
                thead,tbody,tfoot
                                tr
                                    th,td       rowspan,colspan

        Media
            img                                 src="image path"
                                                alt="alternate text"
            
            video                               controls
                source                          src

            audio                               controls
                source                          src
            
            iframe                              src

        Links        
        Forms        





