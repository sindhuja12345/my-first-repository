# my-first-repository

describe('Elements are visible on screen', () => {
    before(() => {
      cy.visit('https://www.amazon.in')
   });
   it("shows login page details", () => {
 
    cy.get('#twotabsearchtextbox').type("watch");
    cy.get('.nav-search-submit > .nav-input').click();
   });
});
     
