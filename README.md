### Notes

<ul>
    <li>
        Routes can be declared in two ways 
        <ol>
            <li>
                <pre>
                  router
                      .route('/')
                      .get((req,res)=>{})
                      .post((req,res)=>{})
                      .put((req,res)=>{})
                      .delete((req,res)=>{})
                </pre>
            </li>
            <li>
                <pre>
                    router.get('/',(req,res)=>{})
                    router.post('/',(req,res)=>{})
                    router.put('/',(req,res)=>{})
                    router.delete('/',(req,res)=>{})
                </pre>
            </li>
        </ol>
    </li>
</ul>
