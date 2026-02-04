# CostHawk Documentation                                                              
                                                                                        
  Official documentation for [CostHawk](https://costhawk.ai) - AI API cost monitoring   
  and optimization platform.                                                            
                                                                                        
  > **Early Alpha** - CostHawk is currently in early alpha testing. [Join the           
  waitlist](https://costhawk.ai) to get early access.                                   
                                                                                        
  ## Overview                                                                           
                                                                                        
  CostHawk helps teams track, analyze, and optimize their AI API spending across        
  providers like Anthropic, OpenAI, and Google.                                         
                                                                                        
  **Key Features:**                                                                     
  - Real-time usage tracking and cost analytics                                         
  - Savings analysis with caching and prompt optimization                               
  - Budget alerts and anomaly detection                                                 
  - MCP server integration for Claude Code/Desktop                                      
                                                                                        
  ## Documentation                                                                      
                                                                                        
  Visit [docs.costhawk.ai](https://docs.costhawk.ai) to view the full documentation.    
                                                                                        
  ### Sections                                                                          
                                                                                        
  - **Getting Started** - Quick setup guide and authentication                          
  - **MCP Server** - Claude Code/Desktop integration                                    
  - **Features** - Usage tracking, savings, alerts, webhooks                            
  - **API Reference** - REST API endpoints                                              
                                                                                        
  ## MCP Server Quick Install                                                           
                                                                                        
  ```bash                                                                               
  # Global installation (all projects)                                                  
  claude mcp add -s user -e COSTHAWK_API_KEY=YOUR_TOKEN_HERE costhawk -- npx --yes costhawk@latest
                                                                                        
  # Project-specific installation                                                       
  claude mcp add -e COSTHAWK_API_KEY=YOUR_TOKEN_HERE costhawk -- npx --yes costhawk@latest        
                                                                                        
  Get your access token from https://costhawk.ai/dashboard/settings in your CostHawk    
  dashboard (requires approved account).                                                
                                                                                        
  Get Early Access                                                                      
                                                                                        
  CostHawk is in early alpha. We're onboarding users in batches to ensure a smooth      
  experience.                                                                           
                                                                                        
  1. https://costhawk.ai                                                                
  2. We'll review your application and send an invite                                   
  3. Once approved, create your access token and start tracking                         
                                                                                        
  Links                                                                                 
                                                                                        
  - https://costhawk.ai                                                                 
  - https://www.npmjs.com/package/costhawk                                              
  - https://docs.costhawk.ai                                                            
                                                                                        
  License                                                                               
                                                                                        
  MIT                                                                                   
  ```                    
