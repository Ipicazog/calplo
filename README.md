# calplo

RUDIMENTARY PROGRAM FOR FIRST CONSISTENCY CHECKING OF EQUATIONS 
YT video: https://youtu.be/oK2JOIbMpUo
If copy, paste, and improvment, please share back

    ·   OPERATIONS:
        
        - Addition:       +
        - Substraction:   -
        - Multiplication: * 
        - Division:       /   
        - Power n:        **n
        - Square root:    sqrt(...)=(...)**(1/2)
        - N root:         (...)**(1/n)  
        - Exponential:    exp(...)
        - Logaritmus:     log(...)
 
 
        
    ·   PROGRAM MODES: 

        MODE 1 : VECTORIAL CALCULUS
                 EXAMPLE:  r=(x(u,v,k),y(u,v,k),z(u,v,k))

                (1) Addition
                (2) Substraction
                (3) Scalar product & vectorial product
                (4) Gradient of each component, divergence, and rotational
                (5) Straight line defined by two points
                (6) Plane defined by three points
         
        MODE 2 : SCATTERING PLOT 
         
                (1) Periodic arrangement in x-axis
                (2) Random arrangement in x-axis

        MODE 3 : IMPLICIT CURVES WITH CLEAR y=f(x)
                 EXAMPLE EXPONENTIAL: f(x)=exp(3*x+2)

                (1) Solve
                (2) Evaluate at a point
                (3) Plot
                (4) Derivate
                (5) Integrate
                    (1) Definite
                        (1) Initial and final limit
                        (2) Initial limit only
                        (3) Final limit only
                    (2) Indefinite

        MODE 4 : IMPLICIT CURVES f(x,y)  
                 EXAMPLE CIRCLE: x**2+y**2-4=0

                (1) Solve as x(y), y(x)
                (2) Solve system

         MODE 5 : PARAMETRIC CURVES r=(x(t),y(t),z(t)) 
                  EXAMPLE DUMP SPIRAL:  x(t)=t*cos(t) ; y(t)=t*sin(t) ; z(t)=t

                (1) Plot 
                (2) Analysis
                    (1) Derivatives
                    (2) Unit tangent vector, Principal unit normal vector, and Binormal vector
                    (3) Curvature, Torsion, and Radius of curvature

        MODE 6 : IMPLICIT SURFACES WITH CLEAR z=f(x,y) 
                 EXAMPLE PLANE:3*x+4*y+5 

                (1) Solve as x(y) , y(x)
                (2) Plot

        MODE 7 : IMPLICIT SURFACES f(x,y,z)
                 EXAMPLE TORUS: (x**2 +y**2+z**2+5**2-10**2)-4*(x**2+y**2)*5**2

                (1) Solve as x(y,z)

        MODE 8 : PARAMETRIC SURFACES r=(x(u,v),y(u,v),z(u,v))
                 EXAMPLE TORUS: x(u,v)=(10+5*cos(u))*cos(v) ; y(u,v)=(10+5*cos(u))*sin(v) ; z(u,v)=5*sin(u))

                (1) Plot 
                (2) Analysis
                    (1) Partial derivatives
                    (2) Unit tangent vector
                    (3) First fundamental form
                    (4) Unit normal vector
                    (5) Second fundamental form
                    (6) Gaussian curvature
                    (7) Mean curvature
                    (8) Principal curvatures 

        MODE 9 : IMPROVE LOOKING 

                (1) Calculate number
                (2) Algebraic expression (ctrl+d to close)

        MODE 0 : EXIT                                             Ctrl+c to close at anytime
