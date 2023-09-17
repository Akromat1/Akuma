<script>
export let rounded=true
</script>
<button
class:active={rounded}>
    
    <slot>
       dscazcd 
    </slot>
</button>
<style>
    .active{
       border-radius: 50% 50%;
    }
button {
    padding: 14px 20px;
    border-radius: 12px;
    background-color:#007AFF ;
    color: white;
    border: none;
    display: flex;
    align-items: center;
    justify-content: center;
    column-gap: 4px;
}
button:hover {
    box-shadow: 0 0 0 99999px inset rgba(0, 0, 0, 0.1);
  }

  button:active {
    box-shadow: 0 0 0 99999px inset rgba(0, 0, 0, 0.2);
  }

</style>