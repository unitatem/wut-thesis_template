# Respect
This template was created thanks to knowledge and wisdom of many powerful Latex Wizards from Stackoverflow guild. Pay them a tribute and use this template freely.

# Useful boilerplates
## Insert image
```
\begin{figure}[htbp]
    \centering
    \includegraphics[scale=1.0]{image_name_with_extension}
    \caption{caption_text.}
    \label{fig:this_image_label}
\end{figure}
```

## Insert table
```
\begin{table}[htbp]
    \caption{caption_text.}
    \label{tab:this_table_label}
\begin{tabular}{|c|c|}
\hline
a & b \\ \hline
c & d \\ \hline
\end{tabular}
\end{table}
```

## Insert code listing
```
\begin{lstlisting}[%
caption={caption_text.},%
label={lst:this_listing_label},%
captionpos=t%
]
#include <iostream>
int main() 
{
    std::cout << "Hello, World!";
    return 0;
}
\end{lstlisting}
```

## Cite
Author (year)
```
\textcite{book_label}

```
(Author, year)
```
\cite{book_label}
```

# User defined
See: latex/config/user_defined.tex

## Name from code
```
\code{name_from_code} 
```

## Matrix or vector
```
\mat{A}
```


# References:
Warsaw University of Technology  
Faculty of Electronics and Information Technology  
http://www.elka.pw.edu.pl/Studia/Kalendarz-ustalenia-plan-zajec/Prace-Dyplomowe  
