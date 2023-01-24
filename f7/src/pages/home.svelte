<Page name="home" id="home">

  <Navbar>
    <NavTitle>
      <h1 class="title">Lorenzo Rizzolo</h1>
    </NavTitle>
  </Navbar>

  <center>
    <Card expandable>
      <CardContent padding={false}>
        <div class="card" style="height: 300px">
          <CardHeader textColor="white" class="display-block">
            Curriculum (CV)<br>
            <small style="opacity: 0.8">Scarica il PDF</small>
          </CardHeader>
          <Link cardClose color="white" class="card-opened-fade-in" style="position: absolute; right: 15px; top: 15px" iconF7="xmark_circle_fill" />
        </div>
        <div class="card-content-padding">
          contenuto
        </div>
      </CardContent>
    </Card>
    
</Page>


<script>
  
  import {
    Accordion, 
    AccordionItem, 
    AccordionContent,
    Icon,
    Card,
    CardContent,
    CardHeader,
    Page,
    Navbar,
    NavLeft,
    NavTitle,
    NavTitleLarge,
    NavRight,
    Link,
    Toolbar,
    Block,
    BlockTitle,
    List,
    ListItem,
    Row,
    Col,
    Button, 
    theme, 
    TreeviewItem, 
    Treeview,
    Subnavbar, 
    Searchbar, 
    Menu, 
    MenuItem 
  } from 'framework7-svelte';


  export let f7route, f7router; // just to remove debug message
</script>