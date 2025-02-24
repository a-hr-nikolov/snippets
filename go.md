##### ERRORS
- **ier** - Return on error
- **ire** - Return on error
- **iref** - Return on error with format wrap
- **irne** - Return val, err on error
- **irnef** - Return val, err on error with format wrap
- **ilpe** - Log on error
- **ilfexit** - Exit on error

##### RETURNS
- **rnil** - return nil
- **re** - return err
- **ref** - return err format wrap
- **rne** - return nil, err
- **rnef** - return nil, err format wrap

##### FORMATTING
- **fms** - fmt.Sprintf()
- **fme** - fmt.Errorf()
- **fmp** - fmt.Printf()
- **fmpl** - fmt.Println()

##### LOGS
- **lo** - log any
- **le** - log err
- **lf** - log fatal
- **lff** - log fatalf

##### CONTROL FLOW
- **frv** - For _, v range on values
- **frkv** - For k, v range on values
- **frf** - for full
- **swc** - switch case
- **slc** - select case
- **cs** - case clause
- **lok** - lock unlock

##### MISC
- **ctxb** - ctx := context.Background()
- **ctxt** - ctx := context.TODO()
- **ap** - append to slice
- **map** - map declaration

##### TYPES
- **tys** - type Struct struct
- **stj** - `json:field`
- **tyi** - type Interface interface
- **ne** - func NewStruct() *Struct

##### FUNCTIONS
- **pkgm** - package main and main function
- **fn** - function declaration
- **meth** - method declaration
- **fmain** - main function
- **defun** - defer IIFE
- **gofun** - gofunc IIFE

##### HTTP
- **wr** - http ResponseWriter *Request
- **hfunc** - http.HandleFunc
- **fhand** - http handler declaration
- **rd** - http.Redirect
- **herr** - http.Error
- **las** - http.ListenAndServe
- **sv** - http.Serve

##### TESTING
- **tdt** - table driven test
- **tf** - test function
- **bf** - benchmark function
- **bfo** - benchmark function old style
- **ef** - example function
