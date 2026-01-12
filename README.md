# Angular-dashboard-sample
This is a sample Angular application demonstrating reusable components, API integration, and responsive UI design.  
- Angular (v15+ compatible) 
- Modular component structure 
- REST API integration 
- Responsive UI using Bootstrap 
- Clean service-based architecture
- 
//
@Injectable({ providedIn: 'root' })

export class ProductService { 

  private apiUrl = 'https://api.example.com/products';
  
  constructor(private http: HttpClient) {} 
  
  getProducts() { 
  
    return this.http.get(this.apiUrl);
    
  } 
  
} 

//
