Many different times we need to know how we can select some element because is so normal to search specification or maybe we can select and entire element and is so useful to know how we can achieve it.


-------------------------------------- Attribute ---------------------------------------
We need to remember what is a attribute inside a label because it's necessary.
All attribute is any modification label as "src, href,class,type..." and we can use in each label.

                    img {
                        width: 100%;
                    }

                    For all the img with "saul.png"
                    img[src="saul.png"]  {
                        width: 100%;
                    }

                    For all lasted with .png
                    img[src$="png"]  {
                        width: 100%;
                    }

                    For all started with
                    img[src^="saul"]  {
                        width: 100%;
                    }

-------------------------------------- Descendant ---------------------------------------
More specific for children " > " where the target must be direct son 

                    ol li{
                        font-style: italic;
                        letter-spacing: 2px;
                        font-weight: 100;
                    }

                    ol li span {
                        color: green;
                    }

                    ol > span {
                        color:aqua;
                    }
                    
-------------------------------------- Next to ---------------------------------------
For all the element next to an specific label. "For all the p next to a H3"
                    /* Next to (first) */
                    h3 + p{
                        color: #293;
                        font-style: italic;
                    }

                    /* Next to(all next to) */
                    h3 ~ p {
                    font-style: italic;
                    }

-------------------------------------- Specificity ---------------------------------------

We know in HTML and CSS the order that we write the code it's important because is in casqued so we can omitted that using .
