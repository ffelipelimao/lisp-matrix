(defun fatorial (n)
   (if (= n 0)
     1
   (* n (fatorial (1- n)))
   )
)

(defun somalistafatorial(lista)
  (if(null lista)
    0
  (+ (fatorial(car lista))(somalistafatorial(cdr lista)))
  )
)

(setq matriz '((4 2 5 4 3) (2 4) (3 1 4)))

(defun somaMatrizEsparsa(matriz)
 (if(null matriz)
  0 
  (+ (somalistafatorial (car matriz))(somaMatrizEsparsa(cdr matriz)))
 )
)
